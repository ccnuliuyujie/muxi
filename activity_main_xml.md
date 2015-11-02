<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent"
    android:layout_height="match_parent" android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <EditText
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:id="@+id/edit1"
        android:layout_weight="2"
        />
    <Button
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="存储"
        android:id="@+id/write"
        android:layout_weight="0.7"
        />
    <Button
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="读取"
        android:layout_weight="0.7"
        android:id="@+id/read"
        />
    <EditText
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:id="@+id/edit2"
        android:layout_weight="6"
        android:editable="false"
        />
    <Button
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="清除"
        android:id="@+id/clear"
        android:layout_weight="1"
        />
</LinearLayout>
