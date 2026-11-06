# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.

## DATE : 30.10.26

## AIM:
To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:


Program to print the text “Hello World”.
```
Developed by: M Mohamed Ashfaq
Registeration Number : 212224240090
```

## MAINACTIVITY.JAVA:

```

package com.example.helloworld;

import android.os.Bundle;
import android.widget.Toast;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        Toast.makeText(this, "onCreate Called",
                Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onStart() {
        super.onStart();

        Toast.makeText(this, "onStart Called",
                Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onResume() {
        super.onResume();

        Toast.makeText(this, "onResume Called",
                Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onPause() {
        super.onPause();

        Toast.makeText(this, "onPause Called",
                Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onStop() {
        super.onStop();

        Toast.makeText(this, "onStop Called",
                Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();

        Toast.makeText(this, "onRestart Called",
                Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onDestroy() {
        Toast.makeText(this, "onDestroy Called",
                Toast.LENGTH_SHORT).show();

        super.onDestroy();
    }
}

```


## ACTIVITY_MAIN.XML:

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:background="#E8E350">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Lifecycle Activity"
        android:textColor="#E81111"
        android:textSize="24sp"
        android:layout_marginBottom="15dp"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Welcome to Android Studio"
        android:textColor="#0292FF"
        android:textSize="24sp"/>

</LinearLayout>

```



## OUTPUT
<img width="2560" height="1440" alt="Screenshot 2026-11-07 003222_edited" src="https://github.com/user-attachments/assets/78e954fa-02cb-4d85-ac5c-dafa93d1568c" />
<img width="2560" height="1440" alt="Screenshot 2026-11-07 003301_edited" src="https://github.com/user-attachments/assets/0bdae189-3f40-4caf-9aaa-7b879b43e9e4" />




## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
