# Email App (Grid Layout demo by Dawn Griffiths and David Griffiths from Head First Android Development)

emailappgridlayout-rybackpo created by Classroom for GitHub

This assignment illustrates the usage of a Grid layout for an Email app.

## Problem:

Design an Android layout for an email application.

## Sample Solution:

https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-rybackpo

## Keypoint:

The xml layout is as follows:
```xml
<GridLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingBottom="@dimen/activity_vertical_margin"
    tools:context=".MainActivity">

    <TextView
        android:text="@string/to"
        android:textSize="15sp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_row="0"
        android:layout_column="0"/>

    <EditText
        android:id="@+id/emailadd"
        android:hint="@string/enter"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_row="0"
        android:layout_column="1" />

    <EditText
        android:hint="@string/message"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="fill"
        android:gravity="top"
        android:layout_row="1"
        android:layout_column="0"
        android:layout_columnSpan="2" />

    <Button
        android:text="@string/send"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:layout_row="2"
        android:layout_column="0"
        android:layout_columnSpan="2"
        android:onClick="onClickSend"/>
</GridLayout>
```

## Screenshots:

![alt tag](https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-rybackpo/blob/master/device-2015-10-05-233421.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-rybackpo/blob/master/device-2015-10-05-233453.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-rybackpo/blob/master/device-2015-10-05-233619.png)
