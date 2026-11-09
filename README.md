# MOB1 Android Mini-Projects

A collection of small Android Studio exercises created for mobile application development coursework. Each folder is an independent practice app, covering a different introductory UI or interaction concept.

## Exercises

| Project | Exercise focus |
| --- | --- |
| `ArticleScreen/` | Article-style screen and content layout |
| `BirthdayCard/` | Birthday greeting/card UI |
| `BusinessCard/` | Business card layout |
| `HappyBirthday/` | Birthday-themed Android app |
| `HelloToast/` | Basic app interaction and feedback |
| `Quadrant/` | Quadrant-based screen layout |
| `TaskDoneScreen/` | Task-completion screen |

## Open and run a project

Each exercise folder contains its own Android project configuration. Open the folder for the exercise you want to run in Android Studio, let Gradle sync, choose an emulator or connected device, and run the app configuration.

For example, to build `ArticleScreen` from a macOS/Linux terminal:

```bash
cd ArticleScreen
./gradlew assembleDebug
```

On Windows, run `gradlew.bat assembleDebug` instead.

## Requirements

- Android Studio and the Android SDK required by the selected project
- A compatible JDK (Android Studio can provide its bundled JDK)
- An emulator or Android device to run the apps

## Repository structure

```text
.
├── ArticleScreen/
├── BirthdayCard/
├── BusinessCard/
├── HappyBirthday/
├── HelloToast/
├── Quadrant/
└── TaskDoneScreen/
```

These are learning exercises rather than one combined application. Build and launch each project from its own directory.
