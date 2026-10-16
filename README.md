# MoMajong for Android

Build the APK in the cloud (no Android Studio needed):

1. Create a free account at github.com and make a new repository (private is fine).
2. Upload everything in this folder (drag the files in on the "Add file > Upload files" page,
   keeping the folders, including the hidden `.github` folder).
3. Open the repo's **Actions** tab. The "Build APK" job starts by itself (about 3-5 minutes).
4. Open the finished run, scroll to **Artifacts**, download **MoMajong-apk**, unzip it.
5. Send `app-debug.apk` to the phone, open it, and allow "Install unknown apps" when asked.

To change the game later, edit `app/src/main/assets/www/index.html` and push again.
