# Syzyf Backup

**Syzyf Backup** is a private backup utility used to maintain encrypted backups of a personal home server.

## Purpose

The application uses Google Drive to store a secondary copy of encrypted backups created with Restic.

## How it works

- Backups are created and encrypted locally on the owner's server.
- Rclone provides access to Google Drive through Google's OAuth 2.0 authorization.
- Backup data is encrypted before it is uploaded.
- The application is intended exclusively for personal use by its owner.

## Data and privacy

The application does not provide services to third parties. No data is collected by or transmitted to an application operator. Google Drive stores the encrypted backup repository.

For further information, see our [Privacy Policy](privacy).

## Contact

For questions about this application, contact:

syzyf.backup@gmail.com
