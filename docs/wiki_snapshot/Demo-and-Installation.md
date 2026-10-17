# Demo & Installation

## Review without installation

- [Watch the walkthrough](https://youtu.be/wgXt_u9OY0M)
- [Explore the Figma prototype](https://www.figma.com/design/owWAblqoTqFcsr2LUPYHXN/TrueMatch-prototype)
- [Read the report](../../report/truematch_report.pdf)

These external links are preserved from the original materials. Playback and access permissions have not been verified in this documentation update.

## Reviewing the Android build

1. Start with the **[walkthrough video](https://youtu.be/wgXt_u9OY0M)** and **[technical report](../../report/truematch_report.pdf)**.
2. For hands-on review, download and extract **[apk/app-debug.zip](../../apk/app-debug.zip)**.
3. Install the extracted APK on a compatible Android device or emulator. The device may require permission to install an app from the browser or file manager.
4. Review the app's requested permissions before enabling the sensing features you want to explore.

**Runtime status:** the archive contains a debug APK. The current availability of the original Firebase project, backend services and demonstration accounts has not been verified. Live functionality may depend on those services and on device sensor/permission support. A reproducible source build and a supported Android-version matrix are not provided in this repository.



## Diagnostic starting points

| Symptom | Check |
| --- | --- |
| APK will not install | Device compatibility and installation permission |
| Authentication/profiles fail | Network and original Firebase availability |
| Activity categories are empty | Permissions, sensors and whether data has been collected |
| Scores or interactions do not update | Original backend/cloud-service availability |

These are suggested checks, not confirmation that the original services still work. No minimum Android version has been established from the available artifacts.

---
[Wiki Home](Home.md) · [Navigation](_Sidebar.md) · [Repository overview](../../README.md)
