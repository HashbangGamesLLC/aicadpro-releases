# AI CAD PRO downloads

**Build it yourself. Plan it together.**

AI CAD PRO is free design software for DIY builders and homesteaders. It puts editable CAD drawings and an AI assistant in one workspace, so you can turn a home, tiny home, shed, workshop, or solar project into clear plans.

- Website: https://aicadpro.onrender.com
- Download: see [Releases](https://github.com/HashbangGamesLLC/aicadpro-releases/releases/latest)

This repository only hosts the Windows installers. The application source is not published here.

## What you need

- A 64-bit Windows PC
- An internet connection for the AI assistant
- A ChatGPT subscription. After installing, open **Settings** and sign in with ChatGPT. You can use an OpenAI API key instead; those requests are billed by OpenAI.

AI CAD PRO is free to download and use. Your projects are saved on your own computer.

## Installing

Run `AI-CAD-PRO-Setup-<version>-x64.exe`. The installer is per-user and lets you choose the install folder.

Early releases are not code-signed yet, so Microsoft SmartScreen may show "Windows protected your PC". Choose **More info**, then **Run anyway**.

To check your download, compare its SHA-256 with the value in the release notes:

```powershell
Get-FileHash .\AI-CAD-PRO-Setup-0.1.0-x64.exe -Algorithm SHA256
```

## Updating

There is no automatic updater yet. Download the newest installer from the website or the Releases page and run it; your projects and settings are kept.

## Support the project

AI CAD PRO stays free whether or not you donate. If you'd like to help fund the engineering input that makes it better: https://gofund.me/265cbf82d
