# Climate Action Companion

A starter native Android app built with Kotlin, Jetpack Compose, and Room.

## Features in this starter
- Climate tip on the home screen
- Record climate-friendly actions by category
- Persist actions locally in a Room/SQLite database
- Delete recorded actions
- A basic built-in climate Q&A helper that works offline

## Important AI note
The current helper uses keyword-based, built-in responses. It is **not** a generative AI model. A cloud AI service usually needs internet access and a backend to protect API credentials. Do not embed a secret API key in the Android app. An on-device model is another option but has additional model-size and device requirements.

## Open and run
1. Install Android Studio and a JDK 17-compatible setup (Android Studio bundles a suitable runtime).
2. Open this folder in Android Studio.
3. Allow Gradle to sync and install any requested Android SDK components.
4. Run on an emulator or a USB-connected Android phone with Developer options and USB debugging enabled.
5. Add an action, close and reopen the app, and confirm the action remains saved.
6. Turn on airplane mode and test recording and viewing actions again.

## Package
`com.levi.climateaction`

## GitHub
Create a repository such as `ClimateActionCompanion`, then use Android Studio's Git/VCS tools or Git command line to commit and push. ChatGPT's GitHub connector access is not assumed by this project.
