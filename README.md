# WalkPet Android prototype

Native Android project (Kotlin + Jetpack Compose), Russian UI.

Included: owner/walker mode switch, demo home screen, urgent/scheduled booking flow, duration selector, demo order confirmation, profile and sample walker cards.

Important: this is a local UI prototype. It does NOT yet have real accounts, backend/database, live map/GPS, chat, notifications, real bookings between users, payment processing, or commission payouts. Sample nearby walkers are placeholders.

## Build an APK
1. Install Android Studio and Android SDK Platform 35.
2. Open this project folder in Android Studio and allow Gradle sync.
3. Connect an Android phone with USB debugging, or start an emulator.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK output: `app/build/outputs/apk/debug/app-debug.apk`.

Package: `ee.walkpet.app`; min Android: 8.0 (API 26).
