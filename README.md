# Doraemon AI

A native Android personal AI companion built in incremental, testable milestones.

## Phase 0: Working Foundation

Implemented in source:
- Native Android launcher screen
- Dark blue/cyan dashboard
- Companion placeholder
- Interactive button and status update
- GitHub Actions workflow for debug APK build and verification
- Basic JVM unit test

Not implemented yet:
- AI chat or provider integration
- Voice recognition or wake word
- Floating overlay
- Persistent memory or tasks
- Routine execution or device synchronization

## Technology

- Kotlin
- Android SDK
- Android Gradle Plugin 8.7.3
- Kotlin Gradle Plugin 2.0.21
- Gradle 8.9
- Java 17
- compileSdk 35, targetSdk 35, minSdk 26

Application ID: `com.doraemon.ai`

## Build with GitHub Actions

1. Commit the project to the repository's `main` branch.
2. Open the Actions tab.
3. Select **Doraemon AI Android Build**.
4. Open the latest successful run.
5. Download the `doraemon-ai-debug-apk` artifact.
6. Extract the artifact ZIP and install `app-debug.apk` on your device.

The first build downloads Gradle and Android dependencies and may take several minutes.

## Installation troubleshooting

- Confirm you downloaded and extracted the workflow artifact ZIP; install the APK inside it, not the ZIP.
- Android may require enabling installation from the trusted browser or file manager used to open your APK.
- An APK signed by a different key generally cannot update an existing installation of the same package. Back up app data before uninstalling an older build.

## Security

Do not commit API credentials, passwords, or private signing keys. A cloud AI provider will need a secure backend for credentials before AI integration is shipped.

## Verification status

The existence of source files does not prove successful compilation or installation. Treat build, test, signature, and device verification as pending until the workflow and device checks have actually completed.
