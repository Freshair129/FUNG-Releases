# FUNG Releases

Public binary releases for FUNG Desktop.

## Latest Desktop release

[Download FUNG for Windows x64](https://github.com/Freshair129/FUNG-Releases/releases/latest/download/FUNG-windows-x64-setup.exe)

The current public beta is `v0.1.0`. It includes the local CPU transcription
runtime and model required by Live Meeting.

## Verify before installing

The Windows installer is not Authenticode-signed, so Windows SmartScreen may
display a warning. Verify the downloaded file against
[`manifests/v0.1.0.sha256`](manifests/v0.1.0.sha256) before installing.

```powershell
Get-FileHash .\FUNG-windows-x64-setup.exe -Algorithm SHA256
```

This repository contains public release binaries and distribution metadata
only. Mobile artifacts are not part of the current release.
