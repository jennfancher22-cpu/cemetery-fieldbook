Cemetery Fieldbook v7.23.0 LIVE — Interface Cleanup

Deployment: unzip and replace index.html in the existing LIVE GitHub repository.
This package does not include user data or OneDrive data.

Changes:
- More compact cemetery distance search controls, no default active search action
- Local-only welcome flow clarified; Get Started can be collapsed without finishing
- Sync status manually opened stays open; opening panel shows latest state
- Cloud privacy notice hidden until storage connected
- Cemetery Change Log reorganized into two collapsible report sections; person review with before/after and Entered in Tree checkboxes; PDF and XLSX retained
- Backups separated from Data Tools with Local Backups, Cloud Backups, Data Integrity Audit, Update from GEDCOM and Start Over
- Legacy technical sync panels hidden from everyday interface; automatic sync engine and safeguards retained
- Full GEDCOM dates remain in editor; result titles show years; temporary refresh-date button hidden
- Editor help icons smaller

Validation performed:
- All 14 executable JavaScript blocks pass Node syntax parsing
- HTML has no duplicate element IDs
- ZIP CRC integrity verified
- Browser-level interaction and actual OneDrive round trip NOT verified in this environment

IMPORTANT: Do not reset or reimport GEDCOM to deploy the update. Preserve your current synced data; inspect the new UI and tests first.
