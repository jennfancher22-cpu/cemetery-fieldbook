Cemetery Fieldbook v7 — OneDrive Backup Phase 1 (TEST only)

This experimental build is isolated from LIVE browser data. It provides:
- Preview of complete v5 backup contents including photo record count and file size
- Microsoft personal OneDrive sign-in using authorization code + PKCE
- Timestamped backups in the OneDrive application folder
- List and download existing cloud backups for manual restore

Cloud sign-in is NOT ready until the developer creates a Microsoft application registration and supplies its client ID.
Use an application registration supporting PERSONAL MICROSOFT ACCOUNTS, with a Single-page application redirect URI of:
https://jennfancher22-cpu.github.io/cemetery-fieldbook/test/
Microsoft Graph delegated permission: Files.ReadWrite.AppFolder. No client secret.

The experimental app does not encrypt cloud backups, synchronize devices, or automatically restore data.
Avoid uploading private real-person genealogy data until the access and recovery controls have been tested.
Use the separate TEST website only; NEVER overwrite LIVE with this file.
