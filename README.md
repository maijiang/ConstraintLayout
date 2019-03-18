# ConstraintLayout
activity.xml
--
    <?xml version="1.0" encoding="utf-8"?>
    <android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:background="#000000"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/RED"
        android:layout_width="50dp"
        android:layout_height="50dp"
        android:layout_marginEnd="295dp"
        android:background="@color/red"
        android:text="RED"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/ORANGE"
        android:layout_width="70"
        android:layout_height="50"
        android:background="@color/orange"
        android:text="ORANGE"
        app:layout_constraintTop_toTopOf="parent"
        tools:layout_editor_absoluteX="157dp" />

    <Button
        android:id="@+id/YELLOW"
        android:layout_width="70"
        android:layout_height="50"
        android:layout_marginStart="96dp"
        android:text="YELLOW"
        android:background="@color/yellow"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/ORANGE"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/GREEN"
        android:layout_width="70"
        android:layout_height="50"
        android:text="GREEN"
        android:background="@color/green"
        tools:layout_editor_absoluteX="87dp"
        tools:layout_editor_absoluteY="72dp" />

    <Button
        android:id="@+id/BLUE"
        android:layout_width="50"
        android:layout_height="50"
        android:layout_marginTop="22dp"
        android:text="BLUE"
        android:background="@color/blue"
        app:layout_constraintTop_toBottomOf="@+id/ORANGE"
        tools:layout_editor_absoluteX="166dp" />

    <Button
        android:id="@+id/INDIGO"
        android:layout_width="70"
        android:layout_height="50"
        android:text="INDIGO"
        android:background="@color/indigo"
        tools:layout_editor_absoluteX="230dp"
        tools:layout_editor_absoluteY="72dp" />

    <Button
        android:id="@+id/VIOLET"
        android:layout_width="0dp"
        android:layout_height="50"
        android:layout_marginTop="94dp"
        android:text="VIOLET"
        android:background="@color/violet"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/RED" />

    </android.support.constraint.ConstraintLayout>
    
color.xml
--
    <?xml version="1.0" encoding="utf-8"?>
    <resources>
    <color name="yellow">#ffff00</color> <!-- 黄色 -->
    <color name="orange">#ffa500</color> <!-- 橙色 -->
    <color name="red">#ff0000</color> <!-- 红色 -->
    <color name="green">#008000</color> <!-- 绿色 -->
    <color name="blue">#0000ff</color> <!-- 蓝色 -->
    <color name="indigo">#4b0082</color> <!-- 靛青色 -->
    <color name="violet">#ee82ee</color> <!-- 紫罗兰色 -->
    </resources>
    
strings.xml
--
    <resources>
    <string name="app_name">ConstraintLayout</string>
    </resources>
styles.xml
--
    <resources>

    <!-- Base application theme. -->
    <style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
        <!-- Customize your theme here. -->
        <item name="colorPrimary">@color/colorPrimary</item>
        <item name="colorPrimaryDark">@color/colorPrimaryDark</item>
        <item name="colorAccent">@color/colorAccent</item>
    </style>

    </resources>
运行结果：
--
![Image text](https://github.com/maijiang/ConstraintLayout/blob/master/constraintLayout.PNG)

    

