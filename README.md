# Aviator Analysis Pro — Android source project

A native Android app for manually recording Aviator multipliers, viewing round history, basic statistics and a chart, and tracking personal risk limits.

## Features
- Add and locally save multiplier history (up to 1,000 rounds).
- History list with timestamps and clear-history action.
- Average, highest, lowest, multiplier distribution, and a recent-round chart.
- Editable bankroll, maximum session loss, and profit target.
- Dark, airplane/crash-game-inspired interface.
- No network access, betting automation, account login, or claims of predicting future rounds.

## Build an APK
1. Install Android Studio (current stable) with Android SDK Platform 35.
2. Open this folder in Android Studio.
3. Allow Gradle sync to complete (internet is needed for first-time Gradle dependency downloads).
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the APK location, usually `app/build/outputs/apk/debug/app-debug.apk`.

This environment did not have the Android SDK or Gradle installed, so an APK could not be compiled here. The source project is included so it can be built in Android Studio.

## Important limitation
Aviator outcomes cannot be reliably predicted from past multipliers. Statistics describe only recorded rounds and are not betting signals or guarantees. Use risk limits for budgeting, not as a promise of profit.
