# Atap releases

Installers for **Atap**, a living notch for Windows 10 and 11, guarded by Kopi the black cat.

Download `AtapSetup-<version>.exe` from [Releases](../../releases/latest). Before running it, check the file against `AtapSetup-<version>.exe.sha256`:

```powershell
Get-FileHash .\AtapSetup-1.0.0.exe -Algorithm SHA256
```

Atap's built-in update check (Settings > About) reads the latest release here and verifies the SHA-256 before installing.

The build is not code-signed yet, so Windows SmartScreen may warn: choose **More info**, then **Run anyway**.
