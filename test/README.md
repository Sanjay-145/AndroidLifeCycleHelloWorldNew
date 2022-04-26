# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min.required Artic Fox)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
## Program to print the text “Hello World”.
## Developed by: P.Sanjay
## Registeration Number : 212220230042

### MainActivity.java:
```
package com.example.ex_no1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Invoked",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStart(){ super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){ super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){ super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){ super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onRestart(){ super.onRestart();

        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){ super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

}
```
### activity_main.xml:
```
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.example.ex_no1">

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.ExNo1">
        <activity
            android:name=".MainActivity"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>

```

## OUTPUT:
![image](https://user-images.githubusercontent.com/75235426/165212500-bcc700b1-31ca-46de-949b-693d65f13be5.png)
![image](https://user-images.githubusercontent.com/75235426/165212544-8759f0e3-a3e2-4627-96d8-c0141effc015.png)
![image](https://user-images.githubusercontent.com/75235426/165212582-35097ad5-0728-41eb-936f-2aad1fa08963.png)
![image](https://user-images.githubusercontent.com/75235426/165212619-f6165d03-7e88-4e89-a70c-d76101b0c347.png)
![image](https://user-images.githubusercontent.com/75235426/165212649-fb26bf27-d99a-413d-aed2-3fb520ccc124.png)
![image](https://user-images.githubusercontent.com/75235426/165212666-e169a9aa-0ada-4fa4-9f86-f40cca4fe060.png)
![image](https://user-images.githubusercontent.com/75235426/165212827-87a30a3c-870a-478b-a1d2-537bb20d6a29.png)





## RESULT:
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.

