V7 GitHub APK build fix

Upload/replace these at repository root:
- .github/workflows/build-apk.yml
- android_app/ (complete folder)

The workflow also self-repairs android_app/settings.gradle, android_app/build.gradle,
and android_app/app/build.gradle and copies root app/src/main into android_app/app/src/main
if the Android source is still stored at the repository root.
