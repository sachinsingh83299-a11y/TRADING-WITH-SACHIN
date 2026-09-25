NIFTY Option AI - GitHub APK Build Package

1. Extract this ZIP on your phone/PC.
2. Upload the extracted files/folders to the ROOT of your GitHub repository.
3. The repository should contain:
   .github/workflows/build-apk.yml
   android_app/
4. Do NOT upload only the ZIP file and expect GitHub Actions to extract it.
5. After committing, open GitHub -> Actions -> Build NIFTY Option AI APK.
6. Run workflow manually, or push to main.
7. When successful, open the run and download the artifact named NIFTY-Option-AI-APK.

The workflow does not use a fixed working-directory of android_app. It locates settings.gradle automatically and uses Gradle 8.11.1, so a Gradle wrapper is not required in the uploaded project.
