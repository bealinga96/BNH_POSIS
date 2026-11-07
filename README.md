# BNH POS & Inventory (Android APK)

1. Create a new GitHub repository and upload **everything in this folder** (including the hidden `.github` folder).
2. Open the repo's **Actions** tab -> **Build Android APK** -> wait for the green check (about 5-8 min).
3. Open the finished run and download **BNH-POS-APK** under *Artifacts*. Unzip it and install `app-debug.apk` on your phone (allow "Install unknown apps").

## Login
- Username: `admin26`
- Password: `myAdmin2026*`

Other staff: log in as admin26 -> Staff -> Edit, then set a username and password for each person.

## Notes
- Data is stored on the phone (offline). Uninstalling the app erases it; back up before that.
- The password is stored only as a salted-style SHA-256 hash, not as plain text. This is local protection suited to a shop device, not server-grade security.
- The APK is a debug build, fine for installing directly. A Play Store release would need a signed release build.
