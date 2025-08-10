# TravelSmart AI - Flutter MVP (Demo)

This ZIP contains a Flutter MVP scaffold for **TravelSmart AI** with:
- Brand theme (Royal Blue #0057B7, Golden Yellow #FFD700)
- Basic screens: Onboarding, Home, Create Trip, Itinerary, Budget, Bookings, Settings
- Language selector (English / Urdu) with simple localization map
- Firebase placeholders (google-services.json & GoogleService-Info.plist)
- Instructions to build (Android APK) on a PC with Flutter installed

## How to run (on a PC)
1. Install Flutter SDK: https://flutter.dev/docs/get-started/install
2. Extract this ZIP.
3. Open the folder in VS Code or Android Studio.
4. Run: `flutter pub get`
5. To run on an Android device or emulator: `flutter run`
6. To build APK: `flutter build apk`

## Notes
- `lib/main.dart` contains TODO markers where you should add your API keys (OpenAI, Maps, Fixer, etc.).
- Firebase files are placeholders (replace with your real `google-services.json` and `GoogleService-Info.plist`).
- This scaffold is intentionally minimal to make building and debugging easier on a mobile-first user

If you want, I can now:
- Prepare a step-by-step Urdu guide for building the APK on a PC / using a friend's PC (since building on mobile alone is difficult).
- Or prepare a short video script you can share with a developer to compile the APK for you.