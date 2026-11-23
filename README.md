# AnalytIQ Inventory — downloads

Windows installer releases for AnalytIQ Inventory. The application source is kept private.

## Latest release — 1.2.2

- [Download and install guide](DOWNLOAD_AND_INSTALL_GUIDE.md)
- [ZIP package](https://github.com/AnalytiqDigital/analytiq-downloads/raw/main/AnalytIQ-Inventory-1.2.2-Windows.zip)
- [Standalone setup executable](https://github.com/AnalytiqDigital/analytiq-downloads/raw/main/AnalytIQ-Inventory-Setup-1.2.2.exe)

SHA-256 of `AnalytIQ-Inventory-1.2.2-Windows.zip`:
`ddbfcbfadf3bcf086fcec5832cdd0cf6953bc4c9e64ac48cbe28b3cfabc8361c`

## What is new in 1.2.2

- Refreshed POS: bounded tile grid with a pinned cart, server-side pagination,
  URL-synced search and category filters, a mobile cart sheet, and keyboard
  shortcuts (`/`, `F9`, `Alt+Shift+C`).
- Dashboard no longer hangs on a repeating analytics request.
- Electron-native SQLite fixes setup on Electron 31, and licence activation now
  binds one key to one computer with a **Deactivate** action in Settings.

## Install (older 1.2.1 release)

1. Open the 1.2.1 release and download `AnalytIQ-Inventory-1.2.1-Windows.zip`.
2. Extract the ZIP, then run `AnalytIQ-Inventory-Setup-1.2.1.exe`.
3. If Windows SmartScreen says *Windows protected your PC*, click **More info → Run anyway** (the installer is not code-signed yet).
4. After the first-run setup, enter your licence key under **Settings → Licence**.

SHA-256 of `AnalytIQ-Inventory-1.2.1-Windows.zip`:
`33a85106731f2dccd3cc30c55bbc5fbc62a3bdfe6508991bff384c8ebd6067de`

## What is new in 1.2.1

- **Licence expiry warning**: a banner from seven days before a licence or
  trial ends, with a **Renew licence** button and the date in the licence
  screen. Keys stay valid through the expiry day.
- **First-run backup prompt**: choose an off-disk backup folder (USB, network
  or cloud-synced); Settings → Backups warns when the folder is missing, on
  the same drive, or no copy has been written.
- **Key delivery and recovery**: keys are emailed and sent on WhatsApp after
  payment when the cloud channels are configured, and the website's
  `/retrieve-key` page recovers a key from the order reference and checkout
  email.
- **Correct support number**: the Help screen now shows WhatsApp
  **0813 971 1767**.
- 1.2.0 features remain: Cash & Bank, restaurant service flow and kitchen
  tickets, 25-product POS paging, batches, price tiers, loyalty and stock
  transfers.

## What was new in 1.2.0

- **Cash & Bank** under Finance: cash drawer, bank, POS and mobile-money
  accounts with live balances. Sales, refunds, voids, expenses and customer
  payments post automatically; move money between accounts and record signed
  adjustments.
- **Restaurant service flow**: order type (dine-in / takeaway / delivery),
  waiter, service charge and tip on the sale, receipt and sale detail.
- **Kitchen order tickets** with an optional separate kitchen printer.
- **POS screen**: products now page five by five (25 per page) with
  Previous / Next paging, and the side menu is easier to read.
- Batches, price tiers, loyalty, counter returns, stock transfers, debtors
  reminders and encrypted offsite backup from the business pack.

## Support

WhatsApp **0813 971 1767** · Calls **0812 431 4217** — Mon–Sat, 9:00–18:00 WAT.

A product of [www.analytiq.ng](https://www.analytiq.ng).
