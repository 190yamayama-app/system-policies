# Privacy Policy

Version: 1.0  
Last Updated: May 3, 2026

Yamashita System Development Office ("we," "us," or "our") sets out the following policy regarding the handling of user personal information and data in connection with the provision of "PocketArchitect" ("the Service").

## Article 1 (Information We Collect)

We collect the following information to provide the Service.

**GitHub Credentials (OAuth Token)**  
Used to access the GitHub API. Stored only on your device and never sent to our servers.

**Firebase Anonymous UID**  
An anonymous identifier automatically issued for server-integrated features such as push notifications. It is not linked to personally identifiable information such as your name or email address.

**FCM Token (Push Notification Token)**  
Used to deliver push notifications such as work completion alerts from the GitHub Copilot agent. Stored on our Firebase server.

**Notification Data**  
The content of work completion notifications and similar data is stored on our Firebase Firestore server.

**Crash Information**  
If the app terminates unexpectedly, technical information such as device model, OS version, and crash location is automatically collected through Firebase Crashlytics. This information does not include personally identifiable information.

## Article 2 (How We Use Your Information)

We use collected information for the following purposes:

1. Communicating with the GitHub API and executing operations requested by the user
2. Sending push notifications
3. Improving app quality and fixing bugs
4. Operating the service securely and preventing unauthorized use

If we use your information for purposes other than those listed above, we will ask for your consent in advance.

## Article 3 (How We Store and Manage Information)

**Information Stored on Your Device**  
The following information is stored only on your device and is never sent to our servers:
- GitHub OAuth token (encrypted with EncryptedSharedPreferences using Android Keystore)
- App settings (language, theme, repository in use, etc.)
- Operation logs (audit log)

**Information Stored on Our Servers**  
The following information is stored on our servers (Firebase):
- FCM token
- Notification data
- Crash information (anonymous)

**Security Measures**  
We implement technical and organizational security measures to protect collected information against unauthorized access, leaks, and tampering.

## Article 4 (Disclosure to Third Parties)

We will not provide user information to third parties except in the following cases:

1. Where the user has provided consent
2. Where required by law
3. Where necessary to protect a person's life, body, or property

## Article 5 (Third-Party Services We Use)

The Service uses the following third-party services. We encourage you to review the privacy policies of each service as well.

**Firebase (Google LLC)**  
Used for push notifications, data storage, and crash analytics.  
[Firebase Privacy Policy](https://firebase.google.com/support/privacy)

**GitHub (GitHub, Inc.)**  
Used for authentication and GitHub API access.  
[GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)

## Article 6 (Your Rights)

You have the following rights:

1. The right to request disclosure of your data held by us
2. The right to request correction of inaccurate information
3. The right to request suspension of use or deletion of your data

To exercise these rights, please use the inquiry form in the App's Settings menu.

## Article 7 (Data Retention)

We retain data only for as long as necessary to fulfill the purposes for which it was collected. If you stop using the Service or request data deletion, we will promptly carry out the deletion procedure. Data stored on your device can be deleted by uninstalling the app.

## Article 8 (Changes to This Privacy Policy)

This Policy may be revised as necessary. You will be notified within the App of any significant changes.

## Article 9 (Contact Us)

For inquiries regarding this Policy, please use the inquiry form in the App's Settings menu.
