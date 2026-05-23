# Android Playground

This repository contains Android experiments and sample apps. The current project is a classic Android to-do application built with Gradle and Java.

## Projects

### ToDo-app

An Android notes and reminder app packaged as `com.example.sqlliteapp` and displayed as `To-Do List`.

Key capabilities:

- Create and update task or note entries
- Store entries locally using SQLite
- Search entries by title or description
- Schedule reminder notifications
- Restore reminder behavior on device boot

## Tech Stack

- Java
- Android SDK 29
- Gradle Android application plugin
- AndroidX AppCompat, Material Components, ConstraintLayout

## Repository Structure

```text
.
├── README.md
└── ToDo-app/
	├── README.md
	├── app/
	├── build.gradle
	├── gradle/
	├── gradlew
	└── settings.gradle
```

## Getting Started

1. Open `ToDo-app` in Android Studio.
2. Ensure the Android SDK for API 29 is installed.
3. Let Gradle sync the project.
4. Run the `app` configuration on an emulator or Android device.

## Notes

- `local.properties` is machine-specific and should not be committed.
- Build outputs and IDE metadata are ignored through the root `.gitignore` and module-level ignore rules.

See `ToDo-app/README.md` for app-specific details.