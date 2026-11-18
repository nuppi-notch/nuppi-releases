# Nuppi releases

Installers for **Nuppi**, a living notch for Windows 10 and 11, guarded by Kopi the black cat. Nuppi was called Atap before; installing it over Atap keeps your data.

Download `NuppiSetup-<version>.exe` from [Releases](../../releases/latest). Before running it, check the file against `NuppiSetup-<version>.exe.sha256`:

```powershell
Get-FileHash .\NuppiSetup-1.0.0.exe -Algorithm SHA256
```

Nuppi's built-in update check (Settings > About) reads the latest release here and verifies the SHA-256 before installing. Releases also carry the same installer as `AtapSetup-<version>.exe`, which is what Atap's update check looks for.

The build is not code-signed yet, so Windows SmartScreen may warn: choose **More info**, then **Run anyway**.
