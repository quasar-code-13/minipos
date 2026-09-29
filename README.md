# Privacy Policy — MiniPOS

**Effective date:** _set to the release date of the version that adds app lock_

> Draft for version 0.2.0 (app lock, required backup account). Publish this
> text (and update the hosted Play Store policy URL) before that version
> goes live.

MiniPOS ("the app") is developed and published by **RainLab**, Dhaka,
Bangladesh. This policy explains what information the app handles, where it
is stored, and the choices you have.

The short version: **your business data belongs to you and stays on your
phone.** We do not run any servers, we do not collect your data, and we
cannot see it.

## 1. Information the app stores

MiniPOS is an offline business record-keeping app. To do its job, it stores
the information you enter:

- Contact records you create (names, phone numbers)
- Sales, purchases, dues, and payment records (amounts, dates, notes)
- App preferences (language, theme)
- If you turn on app lock: a protected form of your PIN and your lock
  settings (see section 3)

All of this is saved **only in the app's private storage on your device**.
It is never transmitted to RainLab or to any third party by default. We have
no access to it.

MiniPOS has no account system of its own and does not collect analytics
about how you use the app. It asks you to sign in with your Google account
so that your records can be backed up to your own Google Drive (section 2).

## 2. Google Drive backup

MiniPOS asks you to sign in with Google when you first use it, so that your
records are protected if the phone is lost, broken or replaced. If you
cannot sign in (for example without an internet connection), the app still
works; it reminds you until you do, and nothing is backed up in the
meantime. Once you are signed in:

- You sign in with your Google account. The app receives your basic Google
  profile information (name, email address, profile picture) to show which
  account is connected, to find your earlier backups when you sign in on a
  new phone and, if you use app lock, to confirm your identity
  when you reset a forgotten PIN (see section 3).
- With your permission, the app uploads a copy of its database to the
  **app-private "application data" folder of your own Google Drive**
  (Google's `drive.appdata` scope). This folder is only accessible to
  MiniPOS on your device; it is not visible in your Drive file list, and it
  is **not accessible to RainLab**.
- Automatic backup is always on while you are signed in. It runs about once
  an hour on Wi-Fi and at least once a day on mobile data, and only uploads
  when something has changed. A phone with no records uploads nothing.
- When you sign in on a new phone or after reinstalling, MiniPOS checks the
  account for earlier backups first and asks whether to restore them. It
  does not back up the new phone until you have answered.
- You can stop backups at any time by signing out on the Backup page.
- Backups are kept on a rotating basis: the most recent copies, one per day
  for the past week and one per week for the past month. Older copies are
  automatically deleted. You can delete all backups at any time by removing MiniPOS's
  access in your Google account settings (Google Drive → Settings → Manage
  apps) or by signing out and deleting data from within the app.

The backup travels directly from your device to Google Drive over an
encrypted connection (HTTPS). No copy passes through, or is stored on, any
RainLab system.

MiniPOS's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the **Limited Use** requirements. In particular, Google user data
is used only to provide the user-facing backup and restore feature and the
app-lock PIN reset described in section 3, is never sold, never used for
advertising, and never read by humans.

## 3. App lock (optional)

You can protect MiniPOS with a PIN, and unlock it with your fingerprint or
face.

- **Your PIN** is stored only on your device, as a salted one-way hash in the
  device's secure storage (Android Keystore). It is never transmitted, is not
  included in backups, and cannot be read by RainLab.
- **Fingerprint and face** checks are performed entirely by your device.
  MiniPOS never receives, stores, or has access to your biometric data; it
  only learns whether the check passed.
- **Resetting a forgotten PIN.** When you set up app lock you can link a
  Google account. To reset the PIN, MiniPOS asks you to sign in to that same
  account and, if your phone has a screen lock, to confirm it. The email
  address of the linked account is stored on your device and compared with
  the account you sign in to. Nothing is sent to RainLab. MiniPOS never sees
  your Google password.
- App lock protects the screen. It does not encrypt the data stored on your
  device or the backup files you export.

Turning app lock off deletes the stored PIN hash, settings and linked email
address from the device.

## 4. Notifications

The app may show notifications on your device, for example service updates
or occasional promotional messages about MiniPOS. Notifications are not
based on your business data, and none of your data is shared to deliver
them. You can turn notifications off at any time in your device's system
settings.

## 5. What we do NOT do

- We do **not** collect, receive, or store your business records
- We do **not** sell or share any data with third parties
- We do **not** show third-party advertising
- We do **not** use your data for advertising or profiling of any kind
- We do **not** collect your location
- We do **not** collect or store biometric data

## 6. Data security

Your data is protected by your device's standard app-sandbox security: no
other app can read MiniPOS's private storage. For backups, protection is
provided by your Google account security — we recommend enabling two-step
verification on your Google account. Because your data lives on your device,
anyone you hand your unlocked phone to can see it; please use a device lock,
and turn on app lock (section 3) if other people use your phone.

## 7. Data retention and deletion

### On your device

- Uninstalling the app, or clearing the app's data from system settings,
  permanently deletes all locally stored MiniPOS data on that device.
- **While you use the app**, your records stay on the phone. For speed, the
  app keeps roughly the **last 90 days** of activity ready in memory, and
  loads older history from on-device storage when you ask for it (for example
  a custom date range in Transactions).
- **Daily totals** used for Statistics are kept as compact per-day summaries
  so charts and range totals can work without loading every old sale.
- **Open dues** (money still owed) and related payment / advance balances are
  kept available for as long as they remain open — they are not removed just
  because they are old.
- A Settings option (**Clean up old sales**) lets you **manually clear settled
  sales older than about six months** to free space, after you back up or
  export. That cleanup runs only on your device, only with your confirmation,
  and does not delete open dues, unused advances, contacts, or daily totals.

RainLab never receives your business records and cannot delete or recover
them for you.

### Google Drive backups

Backups remain in your own Drive until you delete them (see section 2) or
until they are replaced by newer backups under the rotation policy. RainLab
cannot delete, read, or recover them, because we never have access.

Engineering detail for the planned cleanup rules lives in
`docs/data_lifecycle.md` in the project repository.

## 8. Children

MiniPOS is a business tool and is not directed at children under 13. The app
does not knowingly collect personal information from anyone, including
children.

## 9. Changes to this policy

If the app gains features that change how data is handled (for example,
crash reporting or a paid subscription), this policy will be updated before
those features launch, and the effective date above will change. Material
changes will be announced inside the app.

## 10. Contact

For any question about this policy or your data:

**RainLab**
Dhaka, Bangladesh
Email: quasarcode13@gmail.com
