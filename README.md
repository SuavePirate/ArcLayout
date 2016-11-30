# ArcLayout
Xamarin Bindings for the ArcLayout Android Library

Original Android Library: https://github.com/ogaclejapan/ArcLayout 

## Usage
- Add the Binding Library as a reference to your Android project
- Add the ArcLayout view to your layout file

```xml

<com.ogaclejapan.arclayout.ArcLayout
        android:id="@id/arc_layout"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:arc_origin="bottom"
        app:arc_color="#4D000000"
        app:arc_radius="168dp"
        app:arc_axisRadius="120dp"
        app:arc_freeAngle="false"
        app:arc_reverseAngle="false"
        >

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="A"
        android:textColor="#FFFFFF"
        android:background="#03A9F4"
        app:arc_origin="center"
        />

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="B"
        android:textColor="#FFFFFF"
        android:background="#00BCD4"
        app:arc_origin="center"
        />

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="C"
        android:textColor="#FFFFFF"
        android:background="#009688"
        app:arc_origin="center"
        />

</com.ogaclejapan.arclayout.ArcLayout>

```

Full Example Layout:
![Arc Layout Demo1][demo1]

``` xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
                    xmlns:app="http://schemas.android.com/apk/res-auto"
                android:id="@+id/MainLayout"
    android:layout_width="match_parent"
    android:layout_height="match_parent">
  <com.ogaclejapan.arclayout.ArcLayout
        android:id="@+id/arc_layout_top"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:arc_origin="top"
        app:arc_color="#321321"
        app:arc_radius="168dp"
        app:arc_axisRadius="120dp"
        app:arc_freeAngle="false"
        app:arc_reverseAngle="false"
        >

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="A"
        android:textColor="#FFFFFF"
        android:background="#03A9F4"
        app:arc_origin="center"
        />

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="B"
        android:textColor="#FFFFFF"
        android:background="#00BCD4"
        app:arc_origin="center"
        />

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="C"
        android:textColor="#FFFFFF"
        android:background="#009688"
        app:arc_origin="center"
        />

</com.ogaclejapan.arclayout.ArcLayout>
<com.ogaclejapan.arclayout.ArcLayout
        android:id="@+id/arc_layout"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:arc_origin="bottom"
        app:arc_color="#03a9f4"
        app:arc_radius="168dp"
        app:arc_axisRadius="120dp"
        app:arc_freeAngle="false"
        app:arc_reverseAngle="false"
        >

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="A"
        android:textColor="#FFFFFF"
        android:background="#03A9F4"
        app:arc_origin="center"
        />

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="B"
        android:textColor="#FFFFFF"
        android:background="#00BCD4"
        app:arc_origin="center"
        />

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="C"
        android:textColor="#FFFFFF"
        android:background="#009688"
        app:arc_origin="center"
        />

</com.ogaclejapan.arclayout.ArcLayout>
<com.ogaclejapan.arclayout.ArcLayout
        android:id="@+id/arc_layout_center"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:arc_origin="center"
        app:arc_color="#4D123123"
        app:arc_radius="50dp"
        app:arc_axisRadius="50dp"
        app:arc_freeAngle="false"
        app:arc_reverseAngle="false"
        >

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="A"
        android:textColor="#FFFFFF"
        android:background="#03A9F4"
        app:arc_origin="center"
        />

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="B"
        android:textColor="#FFFFFF"
        android:background="#00BCD4"
        app:arc_origin="center"
        />

    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="C"
        android:textColor="#FFFFFF"
        android:background="#009688"
        app:arc_origin="center"
        />
    <Button
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:gravity="center"
        android:text="D"
        android:textColor="#FFFFFF"
        android:background="#009688"
        app:arc_origin="center"
        />
</com.ogaclejapan.arclayout.ArcLayout>
</RelativeLayout>
```

## TODO:
- Add example in the Android Bindings Example repository
- Create Xamarin Component
- Create Nuget Package
[demo1]: https://cloud.githubusercontent.com/assets/6868294/20757562/c5e9e0be-b6e4-11e6-88a4-782c731efe91.png
