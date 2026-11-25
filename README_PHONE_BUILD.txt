LUDO STAR — Android APK build (phone-only workflow)

WHAT THIS IS
A small Android WebView wrapper around the LUDO STAR HTML prototype. It builds a DEBUG APK using GitHub Actions in the cloud, so you do not need to install Android Studio or Unity on your phone.

BUILD FROM YOUR ANDROID PHONE
1. Sign in to GitHub in Chrome. Create a GitHub account if needed.
2. Create a new repository named LudoStarAndroid. Keep it Private if you prefer.
3. Upload the contents of this ZIP to the repository (not the ZIP file itself):
   - Open the repository > Add file > Upload files.
   - Extract this ZIP on your phone first, then select all files and folders inside LudoStarAndroid.
   - Make sure the .github/workflows/build-apk.yml file is included. Some file managers hide dot-folders; if so, enable "show hidden files".
4. Commit the uploaded files to the main branch.
5. Open the repository's Actions tab.
6. Select "Build LUDO STAR APK", then "Run workflow" if it has not started automatically.
7. Wait for the workflow to finish with a green check.
8. Open that workflow run, scroll to Artifacts, and download LUDO-STAR-debug-apk.
9. Extract the downloaded artifact ZIP. It contains app-debug.apk.
10. Tap app-debug.apk to install. Android may ask you to allow Chrome or Files to install unknown apps. Only allow this for the app you downloaded from your own GitHub Actions run.

IMPORTANT
- This creates a DEBUG APK for testing, not a Play Store release.
- The app works offline and wraps the current HTML prototype.
- This prototype has simplified gameplay and is not yet a complete official Ludo rules implementation.
- Online multiplayer, accounts, matchmaking, sound, and polished native assets are not included yet.
- Do not rename the HTML file to .apk; that does not create an Android app.
