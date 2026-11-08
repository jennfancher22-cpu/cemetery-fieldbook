Cemetery Fieldbook v7 — OneDrive reliability TEST

Upload index.html to GitHub repository /test/ ONLY.

Changes:
- Remembers OneDrive access using OAuth offline_access refresh token; silent renewal when possible.
- Reconnect may be needed after browser data cleanup, session revocation or Microsoft SPA renewal expiry.
- Validates cloud upload by downloading the file and checking SHA-256 contents.
- On uncertain upload response, checks for the same filename instead of automatically reuploading.
- Separates a successful backup from a failed cloud-list refresh.

SECURITY: The experimental remembered account uses local browser storage for an OAuth refresh token. Use on trusted devices only. Disconnect removes the local token. Cloud backups are not encrypted by Fieldbook.

LIVE is unchanged. Do not reset data for this test.
