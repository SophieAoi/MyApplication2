# My Application2

An Android app written in Kotlin. Right now it's just the Android Studio starter template: one activity that shows "Hello World!" in the middle of the screen.

## Running it

Open the folder in Android Studio, let Gradle sync, then hit Run with an emulator or a phone plugged in.

Or from the terminal:

```
./gradlew installDebug
```

## Tests

```
./gradlew test                   # unit tests
./gradlew connectedAndroidTest   # needs a device or emulator
```

## Notes

- Min SDK 24, target SDK 37
- Uses XML layouts (not Compose), the main one is `app/src/main/res/layout/activity_main.xml`
- Dependency versions are in `gradle/libs.versions.toml`
