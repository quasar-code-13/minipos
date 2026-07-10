# Privacy Policy — MiniPOS

**Effective date:** July 10, 2026

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

All of this is saved **only in the app's private storage on your device**.
It is never transmitted to RainLab or to any third party by default. We have
no access to it.

MiniPOS does not require an account, does not ask for your identity, and
does not collect analytics about how you use the app.

## 2. Google Drive backup (optional)

The app offers an optional backup feature. If you choose to use it:

- You sign in with your Google account. The app receives your basic Google
  profile information (name, email address, profile picture) solely to show
  which account is connected.
- With your permission, the app uploads a copy of its database to the
  **app-private "application data" folder of your own Google Drive**
  (Google's `drive.appdata` scope). This folder is only accessible to
  MiniPOS on your device; it is not visible in your Drive file list, and it
  is **not accessible to RainLab**.
- Backups are kept on a rotating basis (older copies are automatically
  deleted). You can delete all backups at any time by removing MiniPOS's
  access in your Google account settings (Google Drive → Settings → Manage
  apps) or by signing out and deleting data from within the app.

The backup travels directly from your device to Google Drive over an
encrypted connection (HTTPS). No copy passes through, or is stored on, any
RainLab system.

MiniPOS's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the **Limited Use** requirements. In particular, Google user data
is used only to provide the user-facing backup and restore feature, is never
sold, never used for advertising, and never read by humans.

## 3. Notifications

The app may show notifications on your device, for example service updates
or occasional promotional messages about MiniPOS. Notifications are not
based on your business data, and none of your data is shared to deliver
them. You can turn notifications off at any time in your device's system
settings.

## 4. What we do NOT do

- We do **not** collect, receive, or store your business records
- We do **not** sell or share any data with third parties
- We do **not** show third-party advertising
- We do **not** use your data for advertising or profiling of any kind
- We do **not** collect your location

## 5. Data security

Your data is protected by your device's standard app-sandbox security: no
other app can read MiniPOS's private storage. For backups, protection is
provided by your Google account security — we recommend enabling two-step
verification on your Google account. Because your data lives on your device,
anyone you hand your unlocked phone to can see it; please use a device lock.

## 6. Data retention and deletion

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
- A future in-app option may let you **manually clear old settled sales**
  (for example older than six months) to free space, after you back up or
  export. That cleanup would run only on your device, only with your
  confirmation, and would not delete open dues. Until that feature ships,
  settled history is not auto-deleted.

RainLab never receives your business records and cannot delete or recover
them for you.

### Google Drive backups

Backups remain in your own Drive until you delete them (see section 2) or
until they are replaced by newer backups under the rotation policy. RainLab
cannot delete, read, or recover them, because we never have access.

Engineering detail for the planned cleanup rules lives in
`docs/data_lifecycle.md` in the project repository.

## 7. Children

MiniPOS is a business tool and is not directed at children under 13. The app
does not knowingly collect personal information from anyone, including
children.

## 8. Changes to this policy

If the app gains features that change how data is handled (for example,
crash reporting or a paid subscription), this policy will be updated before
those features launch, and the effective date above will change. Material
changes will be announced inside the app.

## 9. Contact

For any question about this policy or your data:

**RainLab**
Dhaka, Bangladesh
Email: quasarcode13@gmail.com
