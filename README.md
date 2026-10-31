# Hibiki

**A lightweight, privacy-first, fully offline media player for video and music, by HALXNAO.**

Hibiki is the desktop sibling of the Beatzyy music player for Android. It has no accounts, no telemetry and never connects to the internet.

## Download

**[Download the latest version for Windows](https://github.com/<your-username>/hibiki-releases/releases/latest)**

Windows 10 or 11, 64-bit. You do not need to install Java.

## Features

- Two play queues (video and audio) with shuffle, repeat and drag and drop
- "Open with Hibiki" and command-line file arguments
- Real-time audio effects: 10-band equalizer driven by a bass-boost control, 14 reverb presets with an amount control, soft limiter and dither
- Speed and pitch presets from 0.65x to 1.4x, cycled from the control bar or with keyboard shortcuts
- Exporter: save audio (video files become audio-only) as MP3, AAC (M4A), Opus, FLAC or WAV, with your chosen effects and speed applied, batch export and quality choices
- Fully rebindable keyboard shortcuts
- Dark and light themes
- Fullscreen with auto-hiding controls and an on-screen display

## Supported files

- **Video:** mp4, m4v, mkv, mov, avi, webm, wmv, flv, mpg, mpeg, ts, 3gp
- **Audio:** mp3, wav, flac, ogg, oga, opus, m4a, aac, wma, aiff, aif, ape, mka

## Privacy

- Works fully offline. No accounts, no analytics, no network access.
- Your settings and listening history are stored only on your computer, in `%USERPROFILE%\.hibiki`.
- The installer needs no internet connection. The uninstaller asks whether to also delete your settings and history (the default is to keep them).

## Installing

1. Download `Hibiki-Setup-x.y.z.exe` from the [latest release](https://github.com/halxnao/hibiki-releases/releases/latest).
2. Run it and follow the wizard. You can choose the install folder, shortcuts, and whether Hibiki appears in the "Open with" menu for video and audio files. Your current default players are not changed.
3. Updating: run the newer installer over the old version. Your settings and history are kept.

### Windows SmartScreen warning

The installer is not code-signed yet, so Windows may show "Windows protected your PC". Click **More info**, then **Run anyway**. To confirm the file is genuine, compare its SHA-256 with the value in the release notes:

```powershell
Get-FileHash .\Hibiki-Setup-1.0.0.exe -Algorithm SHA256
```

## License

Hibiki is closed-source software, copyright (C) 2026 HALXNAO. The end-user license is shown in the installer and installed with the app. It includes open-source components, including FFmpeg (LGPL v3 or later), listed in `THIRD-PARTY-NOTICES.txt` in the installation folder.
