# Flutter Chatbot 

A simple **Arabic voice chatbot** built with Flutter.

## Features
- Arabic interface with "تحدث الآن" button.
- Speech-to-text (`speech_to_text`).
- Text-to-speech (`flutter_tts`).
- Local reply generation (replaceable with API).
- Calculates and logs average response time.

## Files
- `pubspec.yaml` → Dependencies & config.
- `lib/main.dart` → App UI + STT + TTS + logic.
- `assets/.keep` → Placeholder for assets folder.

## Permissions
In `AndroidManifest.xml`:
```xml
<uses-permission android:name="android.permission.RECORD_AUDIO"/>
<uses-permission android:name="android.permission.INTERNET"/>
```

## Run 
flutter pub get
flutter run
