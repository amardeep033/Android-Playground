# ToDo-app

`ToDo-app` is an Android task and reminder application built with Java and the Android Gradle plugin.

## App Summary

The app displays as `To-Do List` and lets users manage simple note-like tasks with optional reminder date and time values. Entries are stored locally and shown in a searchable list.

## Features

- Add new task entries
- Edit existing entries
- Search by title or description
- Set reminder date and time values
- Show reminder notifications through a notification channel
- Listen for boot events to restore reminder behavior

## Project Details

- App module: `app`
- Package name: `com.example.sqlliteapp`
- Compile SDK: 29
- Min SDK: 16
- Target SDK: 29

## Main Components

- `MainActivity`: lists stored entries and handles search
- `Main3Activity`: add and update flow for entries
- `DBManager`: SQLite database access layer
- `MyReceiver` and `SnoozeReceiver`: reminder and alarm receivers

## Build and Run

### Android Studio

1. Open this `ToDo-app` folder in Android Studio.
2. Allow Gradle sync to finish.
3. Run the `app` module on an emulator or device.

### Command Line

From this folder, use:

```bash
./gradlew assembleDebug
```

## Permissions Used

- `INTERNET`
- `VIBRATE`
- `RECEIVE_BOOT_COMPLETED`
- `WAKE_LOCK`
- `ACCESS_NOTIFICATION_POLICY`

## Tests

- Local unit tests live under `app/src/test`
- Instrumented tests live under `app/src/androidTest`