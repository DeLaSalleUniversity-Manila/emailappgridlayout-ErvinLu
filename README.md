# emailappgridlayout-ErvinLu
emailappgridlayout-ErvinLu created by Classroom for GitHub

This assignment illustrates the usage of a Grid layout for an Email app.


## Problem:

Design an Android layout for an email application. (Refer to Chapter 5 of Head First Android Development by Dawn Griffiths and David Griffiths for more details.)    

https://github.com/DeLaSalleUniversity-Manila/HeadFirstAndroid 

## Sample Solution:

https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-ErvinLu

## Keypoint:

```<GridLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:columnCount="2"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textViewTo"
        android:text="To"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />

    <EditText
        android:id="@+id/editTextEmail"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="fill_horizontal"
        android:hint="Enter email address"/>

    <TextView
        android:id="@+id/textViewSubject"
        android:text="Subject"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />

    <EditText
        android:id="@+id/editTextSubject"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="fill_horizontal"
        android:hint="Enter subject"/>

    <EditText
        android:id="@+id/editTextMessage"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="fill"
        android:gravity="top"
        android:layout_row="2"
        android:layout_column="0"
        android:layout_columnSpan="2"
        android:hint="Message"/>

    <Button
        android:id="@+id/buttonSend"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_row="3"
        android:layout_column="0"
        android:layout_gravity="center_horizontal"
        android:layout_columnSpan="2"
        android:text="SEND"/>

</GridLayout>
```

## Screenshots:

![alt tag](https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-ErvinLu/blob/master/device-2015-10-05-230705.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-ErvinLu/blob/master/device-2015-10-05-230808.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/emailappgridlayout-ErvinLu/blob/master/device-2015-10-05-230857.png)
