# Find Leads

Find Leads is a desktop app from Revoro. It finds local businesses on your own computer and exports
them as a CSV file you can import into a Revoro campaign.

This repository holds the installers only. Download them from the
[latest release](https://github.com/rbk-18/find-leads-releases/releases/latest).

| Platform | File |
|---|---|
| macOS, Apple Silicon | `Find-Leads-0.1.0-mac-arm64.dmg` |
| Windows 10/11, x64 | `Find-Leads-Setup-0.1.0-windows-x64.exe` |

## Version 0.1.0 — SHA-256

```
26df3d7bdc05fffd52b3587c40be3c965f6f30993bc25d9811ebba031fe63b37  Find-Leads-0.1.0-mac-arm64.dmg
21a544a6f6c30dfada6a57a11a44027b2e3622b4a88de7f9bbfcac5ce3272368  Find-Leads-Setup-0.1.0-windows-x64.exe
```

Check a download with `shasum -a 256 <file>` (macOS) or `Get-FileHash <file>` (Windows PowerShell).

## Good to know
- The Mac app is not notarised by Apple and the Windows installer is not code-signed. macOS and
  Windows will warn that the developer or publisher is not verified.
- Searches run on your computer and need an internet connection. The first search downloads the
  app's own search browser, which takes a few minutes; later searches reuse it.
- Results depend on what is publicly listed and on the data source; a search can be limited or fail.

## Third-party software
The app includes the open-source search engine
[gosom/google-maps-scraper](https://github.com/gosom/google-maps-scraper) (MIT License); its licence
text ships inside the app.
