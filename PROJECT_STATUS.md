# Doraemon AI Project Status

## Repository
- GitHub repository: https://github.com/thousip/ai
- Default branch: main
- Application ID: com.doraemon.ai

## Phase 0 manifest

| Path | Status |
|---|---|
| settings.gradle.kts | Source prepared |
| build.gradle.kts | Source prepared |
| gradle.properties | Source prepared |
| app/build.gradle.kts | Source prepared |
| app/src/main/AndroidManifest.xml | Source prepared |
| app/src/main/java/com/doraemon/ai/MainActivity.kt | Source prepared |
| app/src/main/res/values/strings.xml | Source prepared |
| app/src/main/res/values/colors.xml | Source prepared |
| app/src/main/res/values/themes.xml | Source prepared |
| app/src/test/java/com/doraemon/ai/ExampleUnitTest.kt | Source prepared |
| .gitignore | Source prepared |
| .github/workflows/build.yml | Source prepared |
| README.md | Source prepared |

## Status terminology
- PLANNED: requirements documented
- IMPLEMENTED: code written
- BUILT: CI build passes
- INSTALLED: APK installed on device
- VERIFIED: behavior tested
- BLOCKED: a technical or platform limitation prevents progress

## Current milestone
Phase 0 source has been prepared. Build, signature checks, APK metadata checks, installation, and runtime verification remain pending until a workflow run and device tests confirm them.

## Known limitations
- No AI provider or secure backend yet
- No overlay, voice, wake word, database, tasks, or routines yet
- Gradle is installed by CI rather than using a checked-in wrapper
