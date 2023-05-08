# TugasPemroMobile1
<?xml version="1.0" encoding="utf-8"?>


<LinearLayout
    android:orientation="vertical"
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="10dp"
    android:gravity="center"
    tools:context=".MainActivity">


    <TextView
        android:id="@+id/textView4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:textAppearance="@style/TextAppearance.AppCompat.Display2"
        android:text="ADMIN LOGIN"
        />

    <EditText
        android:id="@+id/editTextTextPersonName"
        android:layout_width="315dp"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="textPersonName"
        android:layout_gravity="center"
        android:text="User Name" />

    <EditText
        android:id="@+id/editTextTextPassword"
        android:layout_width="315dp"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="textPassword"
        android:layout_gravity="center"
        android:text="Password"/>

    <Button
        android:id="@+id/button"
        android:layout_width="150dp"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:background="#E0FFFF"
        android:text="LOGIN" />
![admlogin](https://user-images.githubusercontent.com/101730390/236713114-c2ac7f4a-c7cf-442e-a53d-ce4c3b1062a4.png)

- dashboard
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    android:orientation="vertical"
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="10dp"
    tools:context=".MainActivity">

    <android.support.v7.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="200dp"
        app:cardBackgroundColor="#E0FFFF">

        <LinearLayout
            android:layout_width="65dp"
            android:layout_height="85dp"
            android:layout_gravity="bottom|center"
            android:orientation="vertical">

        <ImageView
            android:id="@+id/imageView3"
            android:layout_width="60dp"
            android:layout_height="58dp"
            android:layout_gravity="bottom|center"
            app:srcCompat="@drawable/harga" />
            <TextView
                android:id="@+id/textView3"
                android:layout_width="60dp"
                android:layout_height="wrap_content"
                android:textAlignment="center"
                android:text="harga" />

        </LinearLayout>
        <LinearLayout
            android:layout_width="65dp"
            android:layout_height="85dp"
            android:layout_gravity="bottom"
            android:orientation="vertical">

            <ImageView
                android:id="@+id/imageView1"
                android:layout_width="60dp"
                android:layout_height="58dp"
                app:srcCompat="@drawable/home" />

            <TextView
                android:id="@+id/textView1"
                android:layout_width="60dp"
                android:layout_height="wrap_content"
                android:textAlignment="center"
                android:text="home" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="65dp"
            android:layout_height="85dp"
            android:layout_gravity="bottom|right"
            android:orientation="vertical">

            <ImageView
                android:id="@+id/imageView5"
                android:layout_width="60dp"
                android:layout_height="58dp"
                android:layout_gravity="bottom|center"
                app:srcCompat="@drawable/about" />
            <TextView
                android:id="@+id/textView5"
                android:layout_width="60dp"
                android:layout_height="wrap_content"
                android:textAlignment="center"
                android:text="about" />

        </LinearLayout>
        <TextView
            android:id="@+id/textView2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center_horizontal"
            android:text="e-Order"
            android:textAppearance="@style/TextAppearance.AppCompat.Display2" />

        <ImageView
            android:id="@+id/imageView2"
            android:layout_width="65dp"
            android:layout_height="51dp"
            android:layout_gravity="right"
            app:srcCompat="@drawable/login" />

    </android.support.v7.widget.CardView>


    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="MENERIMA ORDER ONLINE"
        android:textAlignment="center"
        android:textColor="#000000"
        android:textSize="40dp" />

    <Button
        android:id="@+id/button2"
        android:layout_width="match_parent"
        android:layout_height="94dp"
        android:text="ORDER SEKARANG"
        android:textColor="#E0FFFF" />


![dashboard](https://user-images.githubusercontent.com/101730390/236713372-8154155c-4931-4972-a083-997b0c91cdc2.png)

