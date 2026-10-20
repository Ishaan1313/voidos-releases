# Void OS: releases

This repository holds the **releases** and the **installers** of Void OS, a home-server dashboard for Raspberry Pi,
Linux, macOS and Windows. The source is private; releases here are protected (obfuscated) builds, and installs update themselves from here.

## Install

Linux, Raspberry Pi, macOS:

```bash
curl -fsSL https://raw.githubusercontent.com/Ishaan1313/voidos-releases/main/install.sh | bash
```

Windows (PowerShell):

```powershell
irm https://raw.githubusercontent.com/Ishaan1313/voidos-releases/main/install.ps1 | iex
```

The installer downloads the newest release from the [Releases](../../releases) page, checks it, and sets everything up.
Your files and settings are kept on updates.

## License

Copyright (c) 2026, Ishaan Patil | corruptedarc. All rights reserved. See [LICENSE](./LICENSE).
