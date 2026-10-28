<!--
Generated from DayCalc app legal JSON.
Do not edit manually.
Version: 1.5
Last updated: 2026-10-28
-->

# Privacy Policy

---

🌍 **This Document is available in other Languages:**

🇺🇸 English | [🇩🇪 Deutsch](../de-DE/privacy-policy.de.md)

---



**Version:** 1.5

**Last updated:** 2026-10-28

## 1. Overview

DayCalc respects your privacy. The App provides calendar, reminder, and date-calculation features and processes your app-specific data primarily on your device.

## 2. Accounts, Tracking, and Advertising

DayCalc does not require a user account. The App does not sell personal data, use advertising identifiers, or create advertising or tracking profiles.

## 3. Local Data Storage

DayCalc may store the following information locally on your device:

- deadlines created in earlier DayCalc versions that you have not yet moved to Apple Reminders or exported, including their title, due date, category, completion state, and selected notification times
- content-free receipts that let DayCalc verify that a deadline was moved to Apple Reminders; a receipt holds identifiers and a keyed fingerprint, never the reminder's title, notes, or dates
- recent date-calculation results
- calendar visibility, appearance, language, and other app preferences
- technical state needed for the app installation and the one-time migration of existing DayCalc data

If access to a calendar or reminder list becomes unavailable while you are editing, you can choose to save a recovery draft on your device. The draft may contain the values you entered and the original values needed to check for conflicting edits, such as titles, notes, dates, list or calendar identifiers, URLs and locations. Opening a draft does not automatically save it to Calendar or Reminders. You can delete a draft; after a confirmed successful submission, DayCalc attempts to remove it and may retain it for cleanup if removal fails. Drafts with an unresolved save outcome remain on the device without automatically repeating the save. These drafts are not a copy of your Calendar or Reminders database and are not uploaded to a DayCalc server.

This app data is not uploaded to a DayCalc server for the App to operate.

## 4. Calendar and Reminders Access

If you grant calendar access, DayCalc reads the calendar, event, and calendar-metadata values needed by the selected features and writes the changes you confirm through Apple's EventKit framework. Calendar data remains in the iOS-managed calendar store; DayCalc does not copy the entire calendar store into its own persistent database.

If you grant Reminders access, DayCalc reads and writes your reminders through EventKit: the list, title, notes, URL, location, start and due dates, priority, completion state, alarms, and repeat rules of the reminders you view or edit in DayCalc. iOS grants Reminders access only as full access. DayCalc uses it solely to show, create, complete, edit, and delete reminders when you do so in the App. Reminders remain in the iOS-managed Reminders store; DayCalc does not copy the Reminders store into its own persistent database. The recovery drafts described above may retain individual edited values and their original baselines locally.

When you search for a calendar event or reminder location in DayCalc, DayCalc sends the search text you enter to Apple's Maps service through MapKit to retrieve matching places and addresses. DayCalc does not request your device's current location for this search. When you save, the selected place can be written to the event or reminder through EventKit, including an arriving or leaving condition for a reminder if you choose one. Apple processes the search request under its privacy terms.

DayCalc does not inspect Calendar or Reminders content for analytics, diagnostics, product decisions, or support, and does not transmit existing Calendar or Reminders content for those purposes. The user-initiated address search described above sends the search text you enter to Apple Maps. Map previews for event and reminder locations also use Apple Maps to display the relevant area; they do not request your device's current location.

When you expressly export an event to your calendar or move a deadline to Apple Reminders, DayCalc gives the values you confirm to EventKit. Calendar and Reminders accounts and their synchronized services are managed by Apple or the relevant account provider and are subject to their privacy terms. You can change calendar and Reminders permission at any time in iOS Settings.

## 5. Local Notifications

If you selected notification times for deadlines in an earlier DayCalc version, DayCalc may schedule local notifications for those deadlines until you move or export them. Notification requests and their content are managed on the device by iOS. DayCalc does not use remote push notifications for this feature. Alarms of Apple Reminders are delivered by iOS Reminders, not by DayCalc. You can change notification permission at any time in iOS Settings.

## 6. Diagnostics and Error Reporting

DayCalc keeps a bounded technical error log on your device to investigate failures. Entries include the time, an error category and code, a fixed operation name, device model, operating-system version, and app version/build. Local crash entries can include system-delivered crash codes and limited build/symbolication information. iOS controls whether and when these crash reports become available; the log is not a complete record of every crash. DayCalc excludes the contents you enter, calendar/reminder/communication contents, raw error messages, file paths, URLs, device names, and user or installation identifiers from its own log entries.

The local history retains at most 512 entries and 1 MiB of encoded log data, plus database overhead. Entries older than seven days are removed on the next log write or read. Logging remains available when automatic reporting is disabled. In the error-reporting scene you can open a readable JSON report. Creating this report also reads total and available device storage, if available, to help diagnose storage failures. This storage snapshot is included only in the report you choose to view or attach; DayCalc does not add it to automatic error submissions.

If Firebase Crashlytics is available in the distributed App, automatic reporting is enabled by default. You can turn it off in Privacy or Help. New app-reported errors are then withheld; restart the App as indicated to stop an already configured Firebase runtime completely. If Firebase is unavailable or its configuration is absent, automatic reporting remains disabled. Turning reporting off does not delete reports already sent to Google.

When enabled, the sanitized app-reported errors are also sent to Firebase Crashlytics. Crashlytics separately captures native crashes and its own technical context, including stack traces, exception information, device/OS/app information, and memory or storage state. Firebase uses its own Crashlytics installation UUID, Firebase installation ID and session identifiers to process these reports. These reports are therefore not described as fully anonymous. DayCalc supplies no user ID, advertising ID, account profile or additional installation identifier, and does not create cross-app or cross-device tracking. It does not use Firebase Analytics to track product usage.

Google processes Crashlytics reports to diagnose and improve stability. Its documented retention period for crash traces and associated identifiers is 90 days before removal begins. Further details are available in [Firebase Privacy and Security](https://firebase.google.com/support/privacy) and [Firebase's Apple-platform data disclosures](https://firebase.google.com/docs/ios/app-store-data-collection). Firebase's own crash capture is separate from the filtered local log; do not assume both contain identical information.

## 7. Support and External Services

When you choose Email in the error-reporting scene, DayCalc asks whether to attach the diagnostic JSON report. You can attach it, continue without it, or cancel. No email is sent automatically. An attached report includes the technical information and current storage snapshot described above; your email also reveals the sender address you use. Review the report and your message before sending.

If you contact support by email or through GitHub, your message and any information you voluntarily attach are processed by the relevant external service. Do not include information you do not want to share.

DayCalc may use Apple Maps search or open websites, email applications, GitHub, or iOS system interfaces. These external services are outside DayCalc's control and are governed by their own privacy terms.

## 8. Retention and Deletion

You can remove recovery drafts, remaining deadlines, calculation history, and preferences through available App controls. Deleting the App removes app data stored locally by DayCalc, subject to normal iOS backup behavior. Events exported to Apple Calendar are not automatically deleted and must be managed in Calendar. Reminders you create in DayCalc or move from deadlines live in Apple Reminders; DayCalc deletes them only when you delete them in the App, and they otherwise remain manageable in Reminders.

## 9. Security

You are responsible for protecting your device and connected calendar and Reminders accounts with available system security such as a passcode, Touch ID, or Face ID. No storage or transmission system can be guaranteed to be completely secure.

## 10. Children

DayCalc is not directed specifically to children and does not knowingly collect personal data from children.

## 11. Changes

This Privacy Policy may be updated when features or data handling change. The current version will be made available in the App and in the public legal documents.
