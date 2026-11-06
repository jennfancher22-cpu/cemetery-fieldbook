Cemetery Fieldbook v6.1 — public application files

Upload these five files to the ROOT of the cemetery-fieldbook GitHub Pages repository:
index.html
service-worker.js
manifest.webmanifest
icon.svg
README.txt

Do not upload GEDCOMs, private burial JSON files, full backups, or photographs.

WHAT CHANGED
- Data Loading and Protection collapses and expands.
- New version 4 full backups include the complete original burial list, edits, added discoveries, photos, coordinates, and change history.
- Existing backups (versions 1–3) remain importable but do not include the original burial list.
- Local storage keys are unchanged from the live Fieldbook v6.

FIRST TEST AFTER DEPLOYMENT
1. Confirm your original relatives are present without importing anything.
2. Verify the collapsible Data Loading and Protection section.
3. Export a full backup; retain older backups.
4. To verify a clean restore, use a separate private/incognito window and restore that new backup.

WARNINGS
GitHub Pages serves public app code; personal data belongs in local device storage and private backups.
There is no automatic synchronization between devices. Restoring a backup replaces local data on the target device.
Do not uninstall the Android app or clear browser storage during update testing.
