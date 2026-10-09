# Shadowstrike Android wrapper

This is an Android Studio project wrapping the Shadowstrike 3D combat game in a fullscreen WebView. The supplied player model is included at `app/src/main/assets/assets/player.glb`.

## Build an APK
1. Install Android Studio (current stable) and its Android SDK.
2. Open this `ShadowstrikeAndroid` folder in Android Studio.
3. Allow Gradle sync and install any requested SDK components.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show a link to the generated APK. The usual output path is `app/build/outputs/apk/debug/app-debug.apk`.

## Important
- This project folder is not itself a compiled APK. It needs Android Studio/Gradle to compile.
- The game loads Three.js modules from jsDelivr, so an internet connection is needed when playing.
- The game is locked to landscape for a more usable combat layout.
- Test on your target Android phone before distributing. This project has not been compiled or runtime-tested in this environment.
