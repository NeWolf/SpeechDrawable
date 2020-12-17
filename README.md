# SpeechDrawable

```
  <ImageView
        android:id="@+id/iv"
        android:src="@mipmap/ic_launcher"
        app:layout_constraintBottom_toTopOf="@+id/wv"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        android:layout_width="match_parent"
        android:layout_marginBottom="20dp"
        android:layout_height="100dp"/>
```

```
val speechDrawable = SpeechDrawable()
        speechDrawable.lineWidth = 4
        speechDrawable.minHeight = 4
        speechDrawable.setStepWidth(10)
        iv.setImageDrawable(speechDrawable)
        speechDrawable.start()

speechDrawable.setVolume(volume)
```
