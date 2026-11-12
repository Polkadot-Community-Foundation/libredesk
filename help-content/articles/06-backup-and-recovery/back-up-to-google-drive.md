---
title: Backing up your Polkadot app with Google Drive
slug: back-up-to-google-drive
collection: backup-and-recovery
type: how-to
priority: P1
sort_order: 40
excerpt: On the Google Play version, the app saves an encrypted backup to Google Drive when you set up. Check it, or turn it on, in Settings > Backup.
keywords:
  - google drive backup
  - back up account
  - cloud backup
  - not backed up
  - enable google drive
  - backup status
  - backup failed
  - red dot settings
related:
  - restore-your-account
  - back-up-without-google-drive
  - existing-backup-found
  - what-is-a-recovery-phrase
  - payments-backup
flags:
  - F31
status: draft
last_checked: 2026-11-03
---
On the Google Play version, Polkadot backs up your account to Google Drive for you. The backup is encrypted, and it lets you restore your account if you lose your phone or get a new one.
This is done automatically for people who register a username through the version of the Polkadot app downloaded from the Play Store.

The direct download version doesn't use Google Drive. 
See [Back up without Google Drive](back-up-without-google-drive.md).

## Check your backup

Tap **Settings** in the dock, then tap **Backup**. If you see "Account is backed up", there's nothing more to do.

If the Backup row in **Settings** says "Not backed up. Set up a backup to stay protected", or there's a dot on the Settings icon in the dock, your account isn't backed up yet.

## Turn on your backup

1. Tap **Settings** > **Backup**.
2. Tap **Backup Your account**.
3. Choose your Google account and allow access to Google Drive.

You'll see "Creating backup", then "Account is backed up".

If you see "Enable Google Drive", the app can't reach your Google Drive yet. Tap **Enable Google Drive** and follow Google's steps to allow access.

If the app finds a backup of a different account, see ["We found an existing backup" or "Backup conflict"](existing-backup-found.md).

## When the backup happens

The app tries to back up your account automatically when you choose your username. If you skipped Google sign-in, or the backup didn't go through, your account was still created. Turn the backup on using the steps above. <!-- REVIEW F31: the skill says people can turn the backup off, but no switch was found in the app. Add the steps if there is one. -->

A copy of your recovery phrase on paper is a good second backup. See [View your recovery phrase](view-recovery-phrase.md).

"Payments backup", also in **Settings**, is a separate status. See [Payments backups](../04-cash-and-payments/payments-backup.md).

## Related

- [Restore your account on a new phone](restore-your-account.md)
- [What is a recovery phrase?](what-is-a-recovery-phrase.md)
- [Back up without Google Drive](back-up-without-google-drive.md)
