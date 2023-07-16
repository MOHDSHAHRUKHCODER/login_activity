# login_activity
in android a login activity to create a good android application

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".Newregistraion"
    android:background="#F6E338"
    >

    <TextView
        android:id="@+id/textView10"
        android:layout_width="168dp"
        android:layout_height="64dp"
        android:layout_marginTop="72dp"
        android:text="Registration"
        android:textColor="#0B0A0A"
        android:textSize="25sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.497"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <EditText
        android:id="@+id/fullname"
        android:layout_width="300dp"
        android:layout_height="45dp"
        android:layout_marginTop="20dp"
        android:layout_marginBottom="21dp"
        android:ems="10"
        android:hint="Fullname"
        android:inputType="text"
        android:textColor="#0B0A0A"
        android:textColorHint="#0C0101"
        android:textSize="20sp"
        android:textStyle="bold|italic"
        app:layout_constraintBottom_toTopOf="@+id/editTextPhone"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView10" />

    <EditText
        android:id="@+id/editTextPhone"
        android:layout_width="300dp"
        android:layout_height="45dp"
        android:layout_marginTop="20dp"
        android:layout_marginBottom="20dp"
        android:ems="10"
        android:hint="Mobile No"
        android:inputType="number|numberDecimal"
        android:textColor="#0B0A0A"
        android:textColorHint="#0C0101"
        android:textSize="20sp"
        android:textStyle="bold|italic"
        app:layout_constraintBottom_toTopOf="@+id/emailid"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.503"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/fullname" />

    <EditText
        android:id="@+id/emailid"
        android:layout_width="300dp"
        android:layout_height="45dp"
        android:layout_marginTop="20dp"
        android:layout_marginBottom="20dp"
        android:ems="10"
        android:hint="Email"
        android:inputType="textEmailAddress"
        android:textColor="#0B0A0A"
        android:textColorHint="#0C0101"
        android:textSize="20sp"
        android:textStyle="bold|italic"
        app:layout_constraintBottom_toTopOf="@+id/editTextTextPassword5"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.497"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextPhone" />

    <EditText
        android:id="@+id/editTextTextPassword5"
        android:layout_width="300dp"
        android:layout_height="45dp"
        android:layout_marginTop="20dp"
        android:layout_marginBottom="49dp"
        android:ems="10"
        android:hint="Password"
        android:inputType="textPassword"
        android:textColor="#0B0A0A"
        android:textColorHint="#0C0101"
        android:textSize="20sp"
        android:textStyle="bold|italic"
        app:layout_constraintBottom_toTopOf="@+id/signupbutton"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/emailid" />

    <Button
        android:id="@+id/signupbutton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="185dp"
        android:text="Signup"
        android:textColor="#0B0A0A"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>

