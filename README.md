# PaintSync

**PAINT LIKE NEVER BEFORE**

PaintSync exports live paint updates from Photoshop, Illustrator or GIMP to the correct iRacing TGA destination.

## Download

0.5.6 gives every top tab its own outlined surface while keeping the active tab red with black text. Export controls and last-export details appear only on Paint. A persistent bottom strip shows Autosave On/Off/Switching, editor connection and version. Settings is reorganized into Appearance and Language, Source Editor, App Updates and About. All earlier localization, plugin-icon and updater improvements are included.

[Download PaintSync 0.5.6 Beta for Windows x64](https://github.com/arcdtrade/PaintSync-Releases/releases/download/v0.5.6-beta/PaintSync-Setup-0.5.6-Beta.exe) · [Release notes and checksums](https://github.com/arcdtrade/PaintSync-Releases/releases/tag/v0.5.6-beta)

Run Setup, choose your language, enter your iRacing Customer ID, and select the editor plugins you use. English, Spanish, French, German, Brazilian Portuguese and Italian are supported. Settings can change the app language immediately; updates preserve the choice. Setup installs for your Windows account and preserves existing paints and saved settings. The supported desktop target is Windows 11 x64.

Photoshop Link 2.2.4 opens the CCX in Creative Cloud for confirmation. Approve the update and reopen Photoshop to load the white brush dock icon (dark variant for light themes). Illustrator uses a CEP beta panel and enables Adobe developer-panel loading. GIMP uses its current-user GIMP 3 plugin folder. Close PaintSync and selected editors before setup.

## Updates

Use **Settings > Check for updates**, or leave automatic checks enabled (every six hours while the app is running). A pulsing download icon appears in the upper-right app header when an update is found; click it to open the update dialog. It stays steady when Windows animations are disabled. Available updates ask before installation. Stop autosave and let any export finish first. Update downloads must pass Ed25519 signature verification with the publisher key embedded in PaintSync.

The `beta-channel` release holds `appcast.xml`; versioned releases hold the installers. Publisher signing keys and app source are not stored in this public distribution repository.

## Beta status

[Windows checks passed for the published 0.5.6 installer](https://github.com/arcdtrade/PaintSync-Releases/actions/runs/41808021072): six languages, installer and app language persistence, Paint-only actions, persistent autosave footer, Settings group alignment, version metadata and update-icon behavior. Local drawing, state-transition, layout and signature checks passed. The public installer was verified byte-for-byte against the signed build.

0.5.6 includes the earlier installer language-persistence fix. Plugin panel text, external websites and editor-provided diagnostics retain their original language.

Live Photoshop dock rendering and Adobe/GIMP/iRacing export checks and the complete interactive updater flow still require beta testing on a Windows desktop. This beta is not Authenticode-signed, so Windows may show an unknown-publisher warning. Ed25519 update verification is separate from Windows code signing.

All seven corrected logo SVG variants are included with Setup and in the separate branding ZIP. Trading Paints uses a browser-assisted upload handoff; PaintSync does not store a Trading Paints password or silently publish paints.
