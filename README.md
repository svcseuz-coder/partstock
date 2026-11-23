# PartStock — ASC Uzbekistan

Offline spare-parts catalog for ASC (authorized service center) staff.
Search parts by code, description or model, see ASC prices (UZS) and live
warehouse stock, browse brand → model → part type, and check CRM
interchangeability (alternative part codes).

The app works fully offline. No account, no internet connection and no data
collection are required after install.

## Download

**Latest APK (stable link):**

https://github.com/svcseuz-coder/partstock/releases/latest/download/PartStock.apk

All versions: [Releases](../../releases)

## Install (Android)

1. Open the download link on the phone (Telegram / browser).
2. Allow "Install unknown apps" for the app you opened the file with
   (Settings → Apps → Special access → Install unknown apps).
3. If Google Play Protect shows a warning, tap "Install anyway" — the APK is
   signed with a development key, not distributed via Play.
4. The app is ~8 MB; installing an update over an old version works, but if
   install is rejected, uninstall the previous PartStock first (catalog data
   is re-imported from the bundled snapshot).

## Current version

PartStock 2.3.5 — November 2026

- Warehouse stock per warehouse: available, quantity and frozen, plus the total.
  Bin (cell) codes are not shown.
- Fits models card from the CRM interchangeability list (Alternative badges).
- Share a part to Telegram or any other app (description, code, price, stock).
- Visual parts guide: one example code per part type, category photos,
  exploded phone-layout diagram with zoom, RU one-line descriptions.
- XLSX catalog update from the CRM export.

## Notes

- Prices and quantities are shown exactly as imported from the CRM export;
  missing data is never estimated.
- Price is not stock: a part can have an ASC price but no warehouse rows.
- Compatibility is taken only from the CRM interchangeability list.
