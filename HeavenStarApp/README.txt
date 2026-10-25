Heaven Star Home Rent Services - Android project
================================================
Build the APK online (no installs needed):
1. Create a free account at github.com, then click "New repository" (any name).
2. On the repository page choose "uploading an existing file" and drag ALL the
   contents of this folder (including the hidden .github folder) - then Commit.
   Tip: if .github doesn't upload, create the file manually via
   "Add file > Create new file" with the path .github/workflows/build-apk.yml
   and paste the contents of that file.
3. Open the "Actions" tab and wait ~3-5 minutes for "Build APK" to finish (green).
4. Open the run and download "HeavenStarRent-APK" under Artifacts (a zip with the .apk inside).

Or with Android Studio: File > Open > this folder, then Build > Build APK(s).

Notes:
- Data is saved on the phone itself (localStorage). Uninstalling the app or
  clearing its data erases all tenants and payments.
- Default login: admin / admin123 - change it from Settings.
