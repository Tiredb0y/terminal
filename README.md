# Terminal

Customized Windows terminal installer based on [RtlTerminal 1.1.11](https://github.com/mirbehnam/RtlTerminal).

## Download and install

**[Download Terminal-Setup.exe](https://github.com/Tiredb0y/terminal/releases/download/v1.1.11/Terminal-Setup.exe)** · [Release notes and all files](https://github.com/Tiredb0y/terminal/releases/tag/v1.1.11)

- Windows 10 version 2004 (build 19041) or later, x64.
- Self-contained application: a separate .NET installation is not required.
- Run `Terminal-Setup.exe`. Installation is for the current user and does not require administrator privileges.
- Launch **Terminal** from the Start menu or Desktop shortcut. You can also enter `rtt` in a new command prompt or in Explorer's address bar.
- The default installation directory is `%LOCALAPPDATA%\Programs\RtlTerminal`.

## This customized build

- Uses **Terminal** as its displayed application name.
- Starts the shell quietly, without the version, author, or social banners.
- Hides the current-directory toolbar badge while retaining directory history.
- Includes the `rtt` launcher, shortcuts, and a current-user installer/uninstaller.

## Verify the download

Download `SHA256SUMS.txt` from the release and compare it with:

```powershell
Get-FileHash .\Terminal-Setup.exe -Algorithm SHA256
```

Expected SHA-256 for the installer:

```text
691bbff5ee2d5a6377d5de919187c7677588173b1de62459fe85eb4976cb7bc1
```

The installer is unsigned; Windows may display an unknown-publisher warning.

## Distribution and attribution

This repository hosts the customized prebuilt installer, download documentation, and license notices.
The upstream project is [RtlTerminal](https://github.com/mirbehnam/RtlTerminal); its original source does not include this build's local customizations.

Copyright (c) 2026 PersianTerminal contributors. The application is licensed under **GPL-3.0-only**. See [LICENSE](LICENSE) and [COPYRIGHT.txt](COPYRIGHT.txt).
