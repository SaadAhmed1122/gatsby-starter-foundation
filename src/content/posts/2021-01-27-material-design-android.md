---
template: blog-post
title: Material Design Android
slug: Material Design Android
date: 2021-01-27 21:14
description: "Material Design Android Widgets "
---
Registration Form



```
    implementation 'com.google.android.material:material:1.1.0'

```

```
   <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:gravity="center_horizontal"
        android:orientation="vertical"
        app:layout_constraintTop_toBottomOf="@+id/welcome"
        tools:layout_editor_absoluteX="0dp">
        <com.google.android.material.textfield.TextInputLayout
            style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox"
            android:layout_width="350dp"
            android:layout_height="wrap_content"
            android:hint="First Name"
            android:theme="@style/TextInputLayoutStyle">
            <com.google.android.material.textfield.TextInputEditText
                android:id="@+id/fName"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:inputType="textPersonName"/>
        </com.google.android.material.textfield.TextInputLayout>

        <com.google.android.material.textfield.TextInputLayout
            style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox"
            android:layout_width="350dp"
            android:layout_marginTop="16dp"
            android:layout_height="wrap_content"
            android:hint="Last Name"
            android:theme="@style/TextInputLayoutStyle">
            <com.google.android.material.textfield.TextInputEditText
                android:id="@+id/lName"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:inputType="textPersonName"/>
        </com.google.android.material.textfield.TextInputLayout>

        <com.google.android.material.textfield.TextInputLayout
            style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox"
            android:layout_width="350dp"
            android:layout_marginTop="16dp"
            android:layout_height="wrap_content"
            android:hint="@string/email"
            android:theme="@style/TextInputLayoutStyle">
            <com.google.android.material.textfield.TextInputEditText
                android:id="@+id/email"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:inputType="textEmailAddress" />
        </com.google.android.material.textfield.TextInputLayout>

        <com.google.android.material.textfield.TextInputLayout
            style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox"
            android:layout_width="350dp"
            android:layout_height="wrap_content"
            android:layout_marginTop="16dp"
            android:hint="Phone Number"
            android:theme="@style/TextInputLayoutStyle">
            <com.google.android.material.textfield.TextInputEditText
                android:id="@+id/phoneNumber"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:inputType="text|phone" />
        </com.google.android.material.textfield.TextInputLayout>

        <com.google.android.material.textfield.TextInputLayout
            style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox"
            android:layout_width="350dp"
            android:layout_marginTop="16dp"
            android:layout_height="wrap_content"
            android:hint="Organization"
            android:theme="@style/TextInputLayoutStyle">
            <com.google.android.material.textfield.TextInputEditText
                android:id="@+id/organizationName"
                android:layout_width="match_parent"
                android:layout_height="wrap_content" />
        </com.google.android.material.textfield.TextInputLayout>

        <com.google.android.material.textfield.TextInputLayout
            style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox"
            android:layout_width="350dp"
            android:layout_height="wrap_content"
            android:layout_marginTop="16dp"
            android:hint="@string/password"
            app:endIconMode="password_toggle">
            <com.google.android.material.textfield.TextInputEditText
                android:id="@+id/password"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:inputType="textPassword" />
        </com.google.android.material.textfield.TextInputLayout>

        <com.google.android.material.button.MaterialButton
            android:id="@+id/sign_up_btn"
            style="@style/Widget.MaterialComponents.Button.Icon"
            android:layout_width="350dp"
            android:layout_height="64dp"
            android:layout_marginTop="16dp"
            android:layout_marginBottom="32dp"
            android:text="@string/cntn"
            app:backgroundTint="#00bbff"/>
    </LinearLayout>

```