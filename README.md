# ScaleImage

A custom Imageview on Android, user can use this to pinch and zoom the imageview. Normally you can't zoom the native image view, just imnplement this library you can able to pinch and zoom the image softly. 

https://github.com/Yokeshthebouncer/ScaleImage

# Implementation

### Gradle Dependency

```
'implementation 'com.github.Yokeshthebouncer:ScaleImage:1.1.0'
```

### Usage

```
<com.yokesh.scalezoomimage.ScaleImage
       android:id="@+id/img"
       android:layout_width="match_parent"
       android:layout_height="wrap_content"
       app:layout_constraintStart_toStartOf="parent"
       app:layout_constraintTop_toBottomOf="@+id/headerLayout" />
```
       
       
Set the required bitmap image to the imageview programtically 
```
img.setImageBitmap(bitmapData)
```

Any queries please post, Happy to help :) 

There is a sample application, please have a look at it. You will understand.
