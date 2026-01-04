# BladeBeam (Windows) — Installer Guide

This guide shows how to download **BladeBeamsetup.exe** from GitHub and install BladeBeam using the Setup Wizard.

## Download BladeBeamsetup.exe from GitHub

1. Open the BladeBeam GitHub page.
2. Click **Releases** (right side of the repository page).
3. Open the **latest release**.
4. Under **Assets**, download `BladeBeamsetup.exe`.
5. In your browser’s download prompt (or after it downloads), keep the file in your **Downloads** folder (which is under `C:\Users\<YourName>\Downloads`) or move it somewhere else under your user folder like `C:\Users\<YourName>\Desktop`.

Tip: If Windows shows a security prompt when you run the installer, choose **More info → Run anyway** only if you trust that you downloaded it from the official BladeBeam GitHub release.

## Install BladeBeam (Setup Wizard)

1. Double-click `BladeBeamsetup.exe`.
2. Accept the license agreement when prompted.
3. When asked to choose an install location, install **under your user profile** (a path under `C:\Users\...`) unless you have a specific reason to install elsewhere.
   - Example recommended location:
     - `C:\Users\<YourName>\AppData\Local\BladeBeam`
     - or `C:\Users\<YourName>\AppData\Local\Programs\BladeBeam`
4. Choose whether to create a Desktop shortcut (optional).
5. Click **Install** and wait for the wizard to finish.
6. Click **Finish** and launch BladeBeam.

Installing BladeBeam under `C:\Users\<YourName>\...` is recommended because:

- **Write access works normally:** BladeBeam requires write access to write the BladeBeam_log.log file that is necessary for debugging analyses.
- **Fewer permission issues:** Installing into `Program Files` can cause the app to fail when trying to save the log file next to the executable, or require “Run as administrator,” which is inconvenient and not always desirable.
