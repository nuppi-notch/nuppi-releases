# Nuppi releases

Installers for **Nuppi**, a living notch for Windows 10 and 11, guarded by Kopi the black cat. Nuppi was called Atap before; installing it over Atap keeps your data.

**Website:** [nuppi-notch.github.io](https://nuppi-notch.github.io/)

## Get Nuppi

<a href="https://apps.microsoft.com/detail/9P3R8613M3DW?mode=direct"><img src="https://get.microsoft.com/images/en-us%20dark.svg" alt="Get it from Microsoft" height="52"></a>

- **Microsoft Store** (recommended): signed by Microsoft, so Smart App Control and SmartScreen do not block it, and the Store keeps it up to date.
- **[Download NuppiSetup.exe](https://github.com/nuppi-notch/nuppi-releases/releases/latest/download/NuppiSetup.exe)**: the installer, always the newest version. It updates itself from this repository.

## What it does

A small island at the top of your screen. Point at it for:

- **Music** from any player that uses the Windows media controls, with synced lyrics, also right under the closed notch if you like
- **Focus** timer with background sounds, **to-dos** in plain language, a **water** tracker
- **Ask AI** on any selected text (Ctrl+Alt+Q) with the AI provider you choose
- A **shelf** for files and an encrypted **clipboard** history, and copying text from the screen (Ctrl+Alt+T)
- **Prayer times**, weather, your calendar, PC usage, and the battery of Bluetooth headsets and mice
- Windows notifications, volume and brightness in the notch
- **Seven themes**, all drawn in code: Kopi, Glass, Paper, Brutal, Afterglow, Monolith, and Chameleon, which follows Windows' light or dark mode

No account, no ads, no telemetry. See the [privacy policy](https://nuppi-notch.github.io/privacy.html).

## Checking a download

To check a specific version, download `NuppiSetup-<version>.exe` from [Releases](../../releases/latest). Before running it, check the file against `NuppiSetup-<version>.exe.sha256`:

```powershell
Get-FileHash .\NuppiSetup-1.2.0.exe -Algorithm SHA256
```

Nuppi's built-in update check (Settings > About) reads the latest release here and verifies the SHA-256 before installing. Releases also carry the same installer as `AtapSetup-<version>.exe`, which is what Atap's update check looks for.

The installer is not code-signed yet, so Windows SmartScreen may warn: choose **More info**, then **Run anyway**. Where Smart App Control or a work PC's App Control policy blocks it outright ("Error 4551"), install from the Microsoft Store instead.
