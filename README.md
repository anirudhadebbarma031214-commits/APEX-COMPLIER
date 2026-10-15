# APEX HTML COMPILER

A neon-themed Android HTML/CSS/JavaScript editor with live preview.

## Features
- HTML, CSS and JavaScript tabs
- Live website preview in an isolated WebView
- Starter template and reset
- Save and open source text locally in the app
- Export the current HTML document using Android's share sheet
- Responsive dark neon interface with APEX branding

## Build APK
Open **Actions** and select **Build APEX HTML Compiler APK**. The workflow builds a debug APK and uploads it as an artifact. Download the artifact from a successful workflow run and unzip it.

## Local build
Open the `android` folder in Android Studio, allow Gradle sync, then run the app or build the debug APK.

This is a starter editor, not a full desktop compiler. Preview executes JavaScript in the WebView; do not run untrusted code.
