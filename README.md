    <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:src="@drawable/marvin_the_paranoid"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"
        />

    <TextView
        android:text="Code not running?"
        android:id="@+id/hp_malvin"
        android:textColor="#1B5E20"
        android:fontFamily="sans-serif-light"
        android:textStyle="bold"
        android:padding="12dp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentRight="true"
        android:textSize="32sp" />

    <TextView
        android:text="...I'm feeling very depressed."
        android:id="@+id/arthur"
        android:textColor="#1B5E20"
        android:fontFamily="sans-serif-light"
        android:textStyle="bold"
        android:padding="15dp"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentLeft="true"
        android:textSize="32sp"/>
    
    <ImageView
        android:src="@drawable/smiley"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:scaleType="centerCrop"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:paddingBottom="16dp"
        android:paddingRight="16dp"
        />

</RelativeLayout>

