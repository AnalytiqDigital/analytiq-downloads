# AnalytIQ Inventory — Download & Install Guide

**Latest release:** 1.2.2 · **Platform:** Windows 10 or 11, 64-bit · **Status:** unsigned installer

This build includes the refreshed two-pane POS with server-side pagination, the dashboard loading fix, Electron-native SQLite, and one-key-one-computer licence activation.

## 1. Download

- **Recommended — ZIP package:** [AnalytIQ-Inventory-1.2.2-Windows.zip](https://github.com/AnalytiqDigital/analytiq-downloads/raw/main/AnalytIQ-Inventory-1.2.2-Windows.zip)
- **Direct installer:** [AnalytIQ-Inventory-Setup-1.2.2.exe](https://github.com/AnalytiqDigital/analytiq-downloads/raw/main/AnalytIQ-Inventory-Setup-1.2.2.exe)

The ZIP contains only the setup executable. Download from this repository only; do not use third-party mirrors.

## 2. Verify the download

| File | SHA-256 |
| --- | --- |
| `AnalytIQ-Inventory-1.2.2-Windows.zip` | `ddbfcbfadf3bcf086fcec5832cdd0cf6953bc4c9e64ac48cbe28b3cfabc8361c` |
| `AnalytIQ-Inventory-Setup-1.2.2.exe` | `472061f17380fe2d2e18cfb1b1651c49fee408734f3c3d591b77c9fd04e68408` |

In PowerShell, run:

```powershell
Get-FileHash .\AnalytIQ-Inventory-1.2.2-Windows.zip -Algorithm SHA256
```

Compare the printed hash with the table above. If it differs, delete the file and download again.

## 3. Install

1. If you downloaded the ZIP, right-click it and choose **Extract All…**, then open the extracted folder.
2. Run `AnalytIQ-Inventory-Setup-1.2.2.exe`.
3. If Windows SmartScreen says *Windows protected your PC*, click **More info → Run anyway**. The installer is not code-signed yet.
4. Choose an installation folder and complete the setup wizard. A desktop shortcut and a Start menu shortcut are created.
5. Launch **AnalytIQ Inventory & POS** from the desktop shortcut.
6. Complete the first-run setup, then open **Settings → Licence** and activate with your licence key. A key is bound to one computer; use **Deactivate** in Settings before moving to another machine.
7. Under **Settings → Backups**, choose an off-disk backup folder (USB drive, network share or cloud-synced folder). The app warns if the folder is missing or on the same drive.

## 4. Upgrade from an older version

1. Back up your business data from the existing installation first.
2. Close AnalytIQ Inventory completely, including any tray process.
3. Run the 1.2.2 setup executable. It upgrades the existing installation in place.
4. Reopen the app and confirm your data and licence are intact.

## 5. POS shortcuts

- `/` — focus the product search/barcode field
- `F9` — open the payment screen
- `Alt+Shift+C` — clear the current cart

## 6. Support

WhatsApp **0813 971 1767** · Calls **0812 431 4217** — Mon–Sat, 9:00–18:00 WAT.

A product of [www.analytiq.ng](https://www.analytiq.ng). The application source is private; this repository contains installer downloads only.
