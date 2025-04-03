# Backup Strategy

All assets will be backed up to both local storage and cloud services for redundancy.

## Cloud Backup:
- **Primary**: Backblaze B2
- **Secondary**: Dropbox or pCloud for collaborative assets

Automated sync will be set up using **rclone** or **Syncthing** to ensure everything is backed up regularly.

### Schedule:
- Daily backups to Backblaze
- Weekly sync to Dropbox
