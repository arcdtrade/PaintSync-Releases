# PaintSync

**PAINT LIKE NEVER BEFORE**

PaintSync exports live paint updates from Photoshop, Illustrator or GIMP to the correct iRacing TGA destination.

## Download

0.5.7 adds tapered folder tabs that connect to the divider, a flashing UPDATE AVAILABLE pill near the window controls, and #FF0000 across logos, icons and red accents. The dotted mouse-focus artifact is removed, while solid keyboard focus remains. Export controls stay on Paint, the autosave indicator stays in the footer, and Settings retains its grouped layout.

[Download PaintSync 0.5.7 Beta for Windows x64](https://github.com/arcdtrade/PaintSync-Releases/releases/download/v0.5.7-beta/PaintSync-Setup-0.5.7-Beta.exe) · [Release notes and checksums](https://github.com/arcdtrade/PaintSync-Releases/releases/tag/v0.5.7-beta)

Run Setup, choose your language, enter your iRacing Customer ID, and select the editor plugins you use. English, Spanish, French, German, Brazilian Portuguese and Italian are supported. Settings can change the app language immediately; updates preserve the choice. Setup installs for your Windows account and preserves existing paints and saved settings. The supported desktop target is Windows 11 x64.

Photoshop Link 2.2.5 opens the CCX in Creative Cloud for confirmation. Approve the update and reopen Photoshop to load the white brush dock icon (dark variant for light themes). Illustrator Link 0.2.4 includes matching #FF0000 branding and uses a CEP beta panel and enables Adobe developer-panel loading. GIMP uses its current-user GIMP 3 plugin folder. Close PaintSync and selected editors before setup.

## Updates

Use **Settings > Check for updates**, or leave automatic checks enabled (every six hours while the app is running). A flashing red UPDATE AVAILABLE pill appears in the upper-right app header near the window controls when an update is found; click it to open the update dialog. It stays steady when Windows animations are disabled. Available updates ask before installation. Stop autosave and let any export finish first. Update downloads must pass Ed25519 signature verification with the publisher key embedded in PaintSync.

The `beta-channel` release holds `appcast.xml`; versioned releases hold the installers. Publisher signing keys and app source are not stored in this public distribution repository.

## Beta status

[Windows checks passed for the published 0.5.7 installer](https://github.com/arcdtrade/PaintSync-Releases/actions/runs/41810262304): six languages, installer and app language persistence, Paint-only actions, persistent autosave footer, Settings group alignment, version metadata and update-pill text, width, placement and flashing behavior. Local drawing, state-transition, layout and signature checks passed. The public installer was verified byte-for-byte against the signed build.

0.5.7 includes the earlier installer language-persistence fix. Plugin panel text, external websites and editor-provided diagnostics retain their original language.

Live Photoshop dock rendering and Adobe/GIMP/iRacing export checks and the complete interactive updater flow still require beta testing on a Windows desktop. This beta is not Authenticode-signed, so Windows may show an unknown-publisher warning. Ed25519 update verification is separate from Windows code signing.

All seven corrected #FF0000 logo SVG variants are included with Setup and the owner source bundle. Trading Paints uses a browser-assisted upload handoff; PaintSync does not store a Trading Paints password or silently publish paints.
