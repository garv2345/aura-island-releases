# Aura Island

A compact Windows desktop companion for music, AI activity, focus, and everyday tools.

## Download for Windows

**[Get the latest Aura Island release](https://github.com/garv2345/aura-island-releases/releases/latest)**

Download **Aura-Island-Setup-VERSION.exe**, run the installer, and launch **Aura Island** from the Start menu or desktop shortcut.

Requires **Windows 10/11 x64**. You do not need Node.js, npm, or a GitHub account to install the app. Current builds are unsigned; Windows may display an unknown-publisher notice.

## Highlights

- **Music preview:** see the song and artist, hover for playback controls, and open the full player for lyrics.
- **Two activities:** keep music and a running focus timer visible together, with separate hover controls.
- **AI companion:** follow connected agent activity, review permission requests, and configure chat with your own account or API provider.
- **Everyday tools:** clipboard history, quick notes, a file shelf, focus, a local agenda, and weather.
- **Personalization:** character styles, eye colours, outfits, sounds, and configurable shortcuts.
- **Placement controls:** nine docks, fine offsets, display selection, and a Below browser tabs preset.

## First steps

1. Press **Ctrl+Alt+Space** to open Aura. Press **Esc** to collapse it.
2. Play music, then hover over the song summary for playback controls.
3. Start a timer from **Home → Focus** to show the second activity pill.
4. Open **Settings → Island → Position** to move Aura away from browser controls.
5. Enable **General → Behaviour → Collapsed click-through** if you want quick clicks to pass through. Hold over Aura for about **0.6 seconds** to open it.

The tray menu provides settings, notes, clipboard, update checks, and Quit.

## Updating

In Aura, open **Settings → General → Updates**:

**Check for updates → Download update → Restart and install**

Downloads and installation wait for your choice. Optional startup checks look for a new release without installing it automatically.

If your version is older than **0.4.18**, install an updater-enabled release once using the download link above. Portable copies need the Windows installer for the in-app update flow. You can install a new setup release over an existing installation; saved local settings are retained.

## Your data

Each person uses their own settings and account sign-in. Notes, agenda, and settings stay on the PC; clipboard history is opt-in. AI, lyrics, weather, and update features use their respective online services.

## About this repository

This repository hosts Windows installers and update files. Application source is maintained in a separate private repository. Packaged Electron application code is inspectable.

Release assets include the setup executable, its blockmap, **latest.yml** update metadata, and **SHA256SUMS.txt** checksums. Share the [latest release link](https://github.com/garv2345/aura-island-releases/releases/latest) with friends so they can always find the current installer.

