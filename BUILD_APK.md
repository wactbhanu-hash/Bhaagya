# भाग्य — APK/AAB Build

Prerequisites: Android Studio, Android SDK 35, JDK 17.

Debug:
./gradlew assembleDebug
Output: app/build/outputs/apk/debug/app-debug.apk

Release APK:
./gradlew assembleRelease
Output: app/build/outputs/apk/release/app-release.apk

Play Store:
./gradlew bundleRelease
Output: app/build/outputs/bundle/release/app-release.aab

A release build must be signed with the publisher's private keystore before distribution.
