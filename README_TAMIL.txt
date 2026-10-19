GAME TURBO FLOATING PRO - ANDROID PROJECT
Features:
1. Game Turbo floating panel (Android overlay permission required)
2. Movable floating mini window
3. Game mode / launch supported installed games
4. RAM and device performance information
5. Battery percentage + Android battery saver settings shortcut
6. Live network traffic estimate (KB/s, device-wide; not a speed-test result)

IMPORTANT LIMITATIONS:
- This is a source project, not a prebuilt/tested APK.
- Actual CPU/GPU boost, FPS boost, automatic Do Not Disturb, and system-level battery modes cannot be guaranteed because Android/OEM restrictions vary.
- Floating panel needs "Display over other apps" permission.
- Game package names vary by region and version. If a game doesn't launch, use the normal launcher.
- Network speed shown is approximate total device traffic, not the carrier's full line speed.
- The app does not bypass carrier data charges or modify games.

BUILD FROM PHONE (GitHub Actions):
1. Sign in/create GitHub account and create a NEW repository.
2. Upload all files/folders from this project.
3. Open Actions tab and enable workflows if asked.
4. Run "Build Android APK" workflow (or push a commit).
5. Open completed workflow run, download artifact named GameTurboFloating-debug-apk.
6. Extract artifact ZIP to get app-debug.apk and install it on your phone.
For Android Studio, open this folder as a project and build app > assembleDebug.
