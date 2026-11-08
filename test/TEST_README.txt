Cemetery Fieldbook v7 — TEST automatic OneDrive backups

Upload index.html ONLY to the /test folder of the GitHub Pages repository.
Do not upload private GEDCOMs, photographs, or backup JSON files to GitHub.

What's new:
- Explicit opt-in for automatic OneDrive backups.
- Tracks saved record, change-log, photo and GEDCOM data changes.
- While the Fieldbook tab is open and online, uploads after 30 seconds without new changes, with a 2-minute minimum interval in this TEST build.
- Uploads fresh date-stamped JSON files to the user's own OneDrive app folder, confirms content by SHA-256 of a downloaded copy.
- Retains existing manual cloud upload, list, download and direct restore.
- Shows pending/offline/verified status; reconnects when allowed.

Important limitations:
- No uploads while the browser app is closed.
- This is NOT two-way synchronization.
- Unencrypted JSON in OneDrive; use only trusted devices for sign-in.
- Opt-in must be enabled separately on each device.
- Existing uploaded backups are not automatically deleted; OneDrive storage grows with each snapshot.
- Test on disposable TEST records, not on LIVE.
