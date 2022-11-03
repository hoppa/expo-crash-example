# Primer SDK Expo Crash Example
This repo is a minimum reproducable example for an issue where the Android app crashes on launch when the Primer SDK is installed alongside `expo-dev-client`


# Setup
1. Install dependencies with `npm install`
2. Prebuild the Android project with `npx expo prebuild --clean --platform android`
3. Launch an Android emulator
4. Build and launch the app with `npx expo run:android`
5. The app should crash on launch
