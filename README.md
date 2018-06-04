
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/txt_view_top"
        android:padding="30dp"
        android:background="#89c4c4"
        android:layout_alignParentTop="true"
        android:layout_marginBottom="10dp"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_below="@+id/txt_view_top">

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="#17dacd"
            android:textStyle="bold"
            android:padding="30dp" />

        <TextView
            android:layout_width="0dp"
            android:layout_weight="1"
            android:layout_height="wrap_content"
            android:background="#5aec44"
            android:textStyle="bold"
            android:padding="30dp"
            android:layout_marginRight="10dp"
            android:layout_marginLeft="10dp"/>

        <TextView
            android:layout_width="0dp"
            android:layout_weight="1"
            android:layout_height="wrap_content"
            android:background="#17dacd"
            android:textStyle="bold"
            android:padding="30dp"/>

    </LinearLayout>

    <LinearLayout
        android:layout_centerInParent="true"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="#f5580a"
            android:textStyle="bold"
            android:padding="30dp" />

        <TextView
            android:layout_width="0dp"
            android:layout_weight="1"
            android:layout_height="wrap_content"
            android:background="#db4df1"
            android:textStyle="bold"
            android:padding="30dp"
            android:layout_marginRight="10dp"
            android:layout_marginLeft="10dp"/>

        <TextView
            android:layout_width="0dp"
            android:layout_weight="1"
            android:layout_height="wrap_content"
            android:background="#c60522"
            android:textStyle="bold"
            android:padding="30dp"/>

    </LinearLayout>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="#69fc53"
        android:padding="30dp"
        android:layout_above="@+id/txt_view_bottom"
        android:layout_marginBottom="10dp"/>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/txt_view_bottom"
        android:padding="30dp"
        android:background="#0be6ba"
        android:layout_alignParentBottom="true"/>


</RelativeLayout>

