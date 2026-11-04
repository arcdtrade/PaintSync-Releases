# PaintSync

**PAINT LIKE NEVER BEFORE**

PaintSync exports live paint updates from Photoshop, Illustrator or GIMP to the correct iRacing TGA destination.

## Download

0.5.1 fixes the vertical alignment of the NEXT EXPORT label and filename.

[Download PaintSync 0.5.1 Beta for Windows x64](https://github.com/arcdtrade/PaintSync-Releases/releases/download/v0.5.1-beta/PaintSync-Setup-0.5.1-Beta.exe) · [Release notes and checksums](https://github.com/arcdtrade/PaintSync-Releases/releases/tag/v0.5.1-beta)

Run Setup, enter your iRacing Customer ID, and select the editor plugins you use. Setup installs for your Windows account and preserves existing paints and saved settings. The supported desktop target is Windows 11 x64.

Photoshop opens the CCX in Creative Cloud for confirmation. Illustrator uses a CEP beta panel and enables Adobe developer-panel loading. GIMP uses its current-user GIMP 3 plugin folder. Close PaintSync and selected editors before setup.

## Updates

Use **Settings > Check for updates**, or leave automatic checks enabled (every six hours while the app is running). Available updates ask before installation. Stop autosave and let any export finish first. Update downloads must pass Ed25519 signature verification with the publisher key embedded in PaintSync.

The `beta-channel` release holds `appcast.xml`; versioned releases hold the installers. Publisher signing keys and app source are not stored in this public distribution repository.

## Beta status

Windows installation, invalid-ID rejection, settings preservation, native app startup/close, upgrade installation, and uninstall checks passed on the Windows Server 2025 runner. [View the checks](https://github.com/arcdtrade/PaintSync-Releases/actions/runs/41793512475).

Live Adobe/GIMP/iRacing export checks and the complete interactive updater flow still require beta testing on a Windows desktop. This beta is not Authenticode-signed, so Windows may show an unknown-publisher warning. Ed25519 update verification is separate from Windows code signing.

All seven corrected logo SVG variants are included with Setup and in the separate branding ZIP. Trading Paints uses a browser-assisted upload handoff; PaintSync does not store a Trading Paints password or silently publish paints.
