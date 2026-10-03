# VertRunner

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v1.1** (Oct 3, 2026)

- [VertRunner_v1.1_no-install.zip](https://github.com/codenomics/VertRunner/releases/download/v1.1/VertRunner_v1.1_no-install.zip) - 68 KB
- [VertRunner_v1.1_Setup.exe](https://github.com/codenomics/VertRunner/releases/download/v1.1/VertRunner_v1.1_Setup.exe) - 133 KB

What's new in v1.1:

- The window now snaps to the screen edges: drag it to the top to maximize, or to a side to fill half the screen

Older versions are on the [Releases page](https://github.com/codenomics/VertRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find VertRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## More details

```
VERTRUNNER
==========

Converts audio files. Right now: WAV to MP3.
Uses the MP3 encoder that comes with Windows, so nothing else needs installing.


GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
  Download the file ending in _Setup.exe, double-click it and click Install.
  It installs just for you (no admin password) and adds Start menu and
  Desktop shortcuts. Needs Windows 10 or 11 (64-bit).
  To remove it later: Windows Settings > Apps > VertRunner > Uninstall.

OPTION 2 - NO INSTALL (zip)
  1. Download the file ending in _no-install.zip. Right-click it -> Extract
  All... and put the VertRunner folder somewhere it can stay (for example
  Documents). Don't run it from inside the zip.
  2. Double-click VertRunner.exe. Nothing is installed; to remove it, delete
  the folder.

EITHER WAY
  Optional: pin it to Start (right-click it in the Start menu or on the
  desktop -> Pin to Start).

"Windows protected your PC"? Click "More info" -> "Run anyway".
Windows shows that for apps downloaded from the internet that aren't
signed with a paid certificate.


USING IT
--------
1. Drop WAV files (or whole folders) onto the window,
   or click the big box / Add files... (Ctrl+O).
2. Pick the QUALITY:
     320 kbps = best sound, biggest files
     192 kbps = good, about 40% smaller
     128 kbps = smallest
3. Pick where to SAVE TO:
     Same folder as each file  - the MP3 lands next to its WAV
     Choose a folder...        - all MP3s go into one folder
4. Click Convert.

- Your WAV files are never changed or deleted.
- If an MP3 with that name already exists, the new one gets " (2)" added
  instead of replacing it.
- Click a finished file to show it in its folder.
- Click a red one to see why it didn't convert.
- The x on a row removes it from the list (not from your PC).
- Stop halts the conversion; the half-done file is thrown away.

WAVs at unusual sample rates (like 96 kHz) are converted to 48 or 44.1 kHz,
because MP3 doesn't go higher. Surround WAVs become stereo.


GOOD TO KNOW
------------
- "N" editions of Windows need the Media Feature Pack (Settings > Apps >
  Optional features) - VertRunner tells you if it's missing.
- Settings are kept in %APPDATA%\VertRunner\settings.txt.
- If something goes wrong, VertRunner-log.txt next to VertRunner.exe says what.
- To remove VertRunner: delete its folder, plus %APPDATA%\VertRunner.
```

