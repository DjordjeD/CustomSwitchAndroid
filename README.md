# CustomSwitchAndroid

A small Android sample that restyles the stock `Switch` widget with custom drawables.

There are two variants, rounded and rectangular. Each pairs a thumb with a track shape:

```
app/src/main/res/drawable/
├── round_thumb.xml       round_track.xml
└── rectangle_thumb.xml   rectangle_track.xml
```

No custom view code is involved. It's all XML, applied through `android:thumb` and `android:track` in `activity_main.xml`.

## Run

Open the project in Android Studio and run it on an emulator or a device.
