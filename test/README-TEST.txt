Cemetery Fieldbook v7 — TEST OneDrive app-folder initialization fix

Upload index.html ONLY to the repository /test/ folder. Do not replace LIVE.

Change: initialize Microsoft Graph /me/drive/special/approot before uploading or listing backups.
Error messages now include HTTP status and Microsoft Graph error code.

Test: refresh the TEST site, reconnect to personal OneDrive if needed, and try a backup with non-sensitive TEST records. Do not change OneDrive permissions to broader scopes in response to a failed test.

Cloud upload and restore remain experimental and unverified. No changes to LIVE browser data.
