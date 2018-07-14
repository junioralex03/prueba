<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:exported="true"
    tools:context="ado.edu.itla.taskapp.MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="68dp"
        android:text="TaskApp"
        android:textAlignment="center"
        android:textColor="@android:color/holo_blue_dark"
        android:textSize="24sp" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        tools:layout_editor_absoluteX="dp"
        tools:layout_editor_absoluteY="dp">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Usuario"
            android:textSize="24sp" />

        <EditText
            android:id="@+id/txtUsuario"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:ems="10"
            android:inputType="textPersonName" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Contraceña"
            android:textSize="24sp" />

        <EditText
            android:id="@+id/txtClave"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:ems="10"
            android:inputType="textPassword" />


        <Button
            android:id="@+id/btnEntrar"
            android:layout_width="219dp"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:text="Entrar"
            tools:layout_editor_absoluteX="220dp"
            tools:layout_editor_absoluteY="63dp" />

        <TextView
            android:id="@+id/txtRegistrase"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Registrarse"
            android:textColor="@android:color/holo_blue_dark"
            android:textSize="18sp" />


    </LinearLayout>

</LinearLayout>
