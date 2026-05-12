# Tesktop — Mac releases

Auto-update feed and signed builds for [Tesktop](https://tesktop.com), the
Mac → Tesla extended display app.

## Download

Grab the latest DMG from the [Releases page](https://github.com/cemalidev/tesktop-releases/releases/latest).

System requirements:

- macOS 15.6 (Sequoia) or later
- Apple Silicon or Intel Mac
- Tesla with software v11+ for in-car browser support

## Updating

Once installed, Tesktop checks for updates automatically every 24 hours via
[Sparkle](https://sparkle-project.org). You can also choose **Tesktop →
Check for Updates…** in the menubar.

All DMGs are:

- Code-signed by Apple Developer ID Application (Team `2V4WPB7ZPH`)
- Notarized by Apple
- Stapled with a notarization ticket
- EdDSA-signed for the Sparkle auto-updater (rotation-resistant supply-chain
  protection)

## Reporting issues

For bugs or feature requests please email `support@tesktop.com`. Source code
is private; this repository only mirrors release artifacts.

## Appcast

Sparkle reads `appcast.xml` from this repository's `main` branch:

```
https://raw.githubusercontent.com/cemalidev/tesktop-releases/main/appcast.xml
```
