# Privacy Policy

**Effective Date:** April 15, 2026  
**Last Updated:** April 15, 2026

This Privacy Policy describes how EventNote ("we", "our", or "us") collects, uses, and protects your information when you use the EventNote mobile application ("App"). By using the App, you agree to the practices described in this policy.

---

## 1. Who We Are

EventNote is a photography and event management application designed for photographers, videographers, and production professionals. The App helps you manage bookings, clients, schedules, tasks, and team collaboration.

---

## 2. Information We Collect

### 2.1 Information You Provide

**Without an account (offline use):**
- Event details: title, date and time, timezone, location, type of shoot, pricing, prepayment amounts, notes
- Client information: name, phone number, Telegram handle, Instagram handle, website
- To-do tasks and deadlines associated with events
- Event photos and reference images
- Your role (e.g. photographer, videographer, production assistant)

**With a Teams account (optional):**
- Email address and password (used for authentication via Supabase)
- Profile information: full name, phone number, website, profile avatar
- Team event data: event details, member roles, invitations, attached reference images and files (PDFs and documents)

### 2.2 Information Collected Automatically

- **Location data** — collected only when you use the Sun Track feature and only while the App is in use. Used to calculate the sun's position and path for photography planning. Accurate to approximately 100 meters.
- **Device timezone** — used to correctly display and schedule your events.
- **Push notification tokens** — collected when you grant notification permissions, used to deliver local reminders for your events and deadlines.

### 2.3 Purchase and Subscription Information

When you subscribe to EventNote Pro, Apple's App Store and RevenueCat process your transaction. We receive confirmation of your subscription status and entitlements. We do not receive or store your payment card details.

---

## 3. How We Use Your Information

| Purpose | Legal Basis |
|--------|------------|
| Provide core event and client management features | Necessary to deliver the service |
| Sync data to your iCloud account (Pro feature, optional) | Your consent via iCloud settings |
| Enable team collaboration via Supabase | Your consent when creating a Teams account |
| Show sun position and path for your shoot location | Your consent via location permission |
| Send event reminders and deadline notifications | Your consent via notification permission |
| Manage your Pro subscription | Necessary to deliver the service |

We do not use your data for advertising, profiling, or sale to third parties.

---

## 4. Third-Party Services

The App integrates with the following third-party services. Each service has its own privacy policy.

### Apple iCloud / CloudKit
- **Purpose:** Optional background sync of your events, contacts, tasks, and images across your Apple devices.
- **Activated by:** Enabling iCloud sync (Pro feature). Disabled by default.
- **Data shared:** All CoreData records you create in the App.
- **Policy:** [apple.com/legal/privacy](https://www.apple.com/legal/privacy/)

### Supabase
- **Purpose:** Authentication, database storage, and file storage for the Teams collaboration feature.
- **Activated by:** Creating a Teams account.
- **Data shared:** Email address, hashed password, user profile (name, phone, website, avatar), team events, reference images, and invited contacts.
- **Policy:** [supabase.com/privacy](https://supabase.com/privacy)

### RevenueCat
- **Purpose:** Subscription and in-app purchase management for EventNote Pro.
- **Data shared:** Purchase transactions, subscription status, entitlement data, and anonymized device identifiers.
- **Policy:** [revenuecat.com/privacy](https://www.revenuecat.com/privacy)

### Google Places SDK
- **Purpose:** Location search and autocomplete when adding an event location.
- **Data shared:** Search queries you type in the location field.
- **Policy:** [policies.google.com/privacy](https://policies.google.com/privacy)

### Apple StoreKit
- **Purpose:** Processing in-app purchases through the App Store.
- **Data shared:** Transaction data handled entirely by Apple.
- **Policy:** [apple.com/legal/privacy](https://www.apple.com/legal/privacy/)

---

## 5. Data Storage and Security

**Local storage:** The majority of your data is stored on your device in an encrypted SQLite database managed by Apple's CoreData framework. This data never leaves your device unless you opt in to iCloud sync or use the Teams feature.

**iCloud:** When iCloud sync is enabled, your data is stored in your personal iCloud account and governed by Apple's security practices. We do not have access to your iCloud data.

**Supabase:** Data transmitted to Supabase is protected using HTTPS/TLS encryption in transit. Passwords are never stored in plain text.

**Backups:** The App creates local snapshot backups in your device's Documents directory. A maximum of 12 snapshots are kept; older backups are automatically deleted.

We have no analytics services, crash reporting platforms, or advertising SDKs embedded in the App.

---

## 6. Permissions

The App may request the following device permissions:

| Permission | Purpose | Required |
|-----------|---------|---------|
| **Location (When In Use)** | Calculate sun position and path in Sun Track | Optional |
| **Camera** | Capture photos for events and team collaboration | Optional |
| **Photo Library** | Import photos for events and team collaboration | Optional |
| **Notifications** | Deliver event and deadline reminders | Optional |
| **iCloud** | Sync data across your Apple devices (Pro) | Optional |

You can revoke any permission at any time in your device Settings.

---

## 7. Children's Privacy

The App is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us and we will delete it.

---

## 8. Your Rights and Choices

Depending on your location, you may have rights regarding your personal data, including:

- **Access** — request a copy of the data we hold about you.
- **Correction** — update inaccurate data directly within the App or by contacting us.
- **Deletion** — delete your account and associated data. To delete your Teams account and all server-side data, sign in, navigate to Settings, and use the "Delete Account" option, or contact us directly.
- **Portability** — the App's backup feature allows you to export your local data as SQLite snapshots.
- **Withdrawal of consent** — revoke location, camera, photo library, or notification permissions at any time via iOS Settings.

**California residents (CCPA):** We do not sell personal information.  
**EEA/UK residents (GDPR):** We do not transfer personal data outside your region unless using the services listed in Section 4, each of which provides adequate safeguards.

---

## 9. Data Retention

- **Local data** is retained on your device until you delete it or uninstall the App.
- **iCloud data** is retained in your iCloud account under Apple's retention policies.
- **Teams account data** on Supabase is retained until you delete your account.
- **Backup snapshots** are automatically managed; the App retains a maximum of 12 snapshots.

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will revise the "Last Updated" date at the top of this page. We encourage you to review this policy periodically. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 11. Contact Us

If you have questions or requests regarding this Privacy Policy, please contact us at:

**Email:** [eventnoteapp@gmail.com]  
**Developer:** Volodymyr Pysarenko
