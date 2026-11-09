# Superheroes

A scrolling list of Android-themed superheroes, each with a name, a short description and an image.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Superheroes" practice project).

## Features

- `LazyColumn` of six hero cards
- Center-aligned top app bar

## Built with

- Kotlin, Jetpack Compose, Material 3 (custom theme, shapes and typography)
- `Hero` data class and a static `HeroesRepository`
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
