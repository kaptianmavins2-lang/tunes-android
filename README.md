# Tunes Android Starter

A beginner-friendly Android Studio starter project for Tunes, a short-movie and social video app.

## Included in this starter
- Kotlin + Jetpack Compose UI
- Demo login screen
- Home feed with sample video cards
- Like and follow interactions (local demo state)
- Discover, Chat, and Profile navigation placeholders
- Android package name: `com.tunes.video`
- Minimum Android version: Android 6.0 (API 23)

## Important
This is a UI starter, not a production streaming service yet. Login currently only opens the demo app; likes/follows are stored only in screen memory. Video cards are visual placeholders and do not play real videos. No live streaming is included in this first version.

## Open in Android Studio
1. Download and unzip this project.
2. Open Android Studio.
3. Choose **Open** and select the `TunesAndroidStarter` folder.
4. Allow Gradle sync to finish. Use JDK 17 if Android Studio asks.
5. Connect an Android phone with USB debugging enabled, or create an emulator.
6. Press **Run**.

## Recommended next steps
1. Create a Firebase project and register Android app ID `com.tunes.video`.
2. Add Firebase Authentication (email/password) and Cloud Firestore.
3. Add a video upload/storage service and store video metadata in Firestore.
4. Add AndroidX Media3 ExoPlayer for playback.
5. Add chat with Firestore and security rules.
6. Add moderation/report/block tools before public launch.
7. Integrate a live streaming provider in a later version.

Only upload videos you own or have permission to distribute.
