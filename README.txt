Cemetery Fieldbook v6 — Release Candidate (test before publishing)

Contains only public application code. Does NOT include GEDCOM files, burial records, photographs, or backups.

Local test: Open index.html from extracted folder in Chrome. Local file storage is separate from the installed app. Do not assume local testing will inherit your data. Restore a COPY of your recent full backup, and import your private burial list if needed.

GitHub: Once tested, upload only index.html, service-worker.js, manifest.webmanifest, icon.svg, README.txt to repository root. Commit on main and verify Pages deployment success. Never upload private JSON, GEDCOM, backup or photographs.

New: smarter net-change reporting; 3-tab Excel tree report; Excel activity history; compact grouped reports; compact burial rows; aligned statuses; hide separate from clear filters; collapsible Find sections; clickable FG indicators.

Known limitations: no automatic sync between devices, GPS permission needs testing, deleted-discovery semantics need dedicated test. The backup contains fieldwork, photos and change log, but private baseline burial list is stored separately and must already exist in the target browser. Preserve older backups.

Cemetery Fieldbook v6 public release (2026-11-06).
Includes compact navigation and grouped burial/report views, smarter net tree changes, Excel exports, Find a Grave indicator, and photo-attachment history and tree reports.
Only upload the five files in this folder to the public GitHub repository. Never upload a GEDCOM, burial list, photos, or backup.
Before updating, export a full backup. After deployment verify existing records and photo attachments on both devices.
