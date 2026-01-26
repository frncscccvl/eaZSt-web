# Privacy Policy for eaZSt

**Last Updated:** January 25, 2026

**eaZSt** ("the App") is developed by **FRANCIS CACCAVALE** ("we," "us," or "our"). We respect your privacy and are committed to protecting it through our compliance with this policy.

This policy describes the types of information we may collect from you or that you may provide when you use the eaZSt mobile application and our practices for collecting, using, maintaining, protecting, and disclosing that information.

## 1. Data Architecture (Hybrid Model)
eaZSt prioritizes on-device storage for most activities, but utilizes a secure backend server for specific banking integrations where required by security protocols.

* **Platform Integrations (YouTube, Twitch, Patreon):** Authentication tokens and data for these platforms are stored **locally on your device** using secure encryption (iOS Keychain and Android Keystore). We do not sync this data to our servers.
* **Banking Integrations (Plaid):** Due to strict banking security requirements, authentication tokens for bank connections are stored in an **encrypted database on our secure backend server**.

## 2. Information We Collect and How We Use It

### A. Third-Party Service Connections (OAuth)
The App allows you to connect to third-party services to visualize your earnings.

* **Direct Integrations:** For services like YouTube and Twitch, the App communicates directly from your device to the service provider. We do not intercept or store this data on our servers.
* **Banking Services (Plaid):** We use Plaid Inc. ("Plaid") to connect your bank accounts. When you link a bank account:
  1. Plaid collects your login credentials directly (we never see your bank username or password).
  2. Plaid provides our secure server with an **Access Token**.
  3. We use this token to fetch **transaction data** (specifically deposits) to calculate your passive income.
  4. Information collected by Plaid is subject to the [Plaid Privacy Policy](https://plaid.com/legal/#end-user-privacy-policy).

### B. Biometric Data (FaceID / TouchID)
The App uses your device's biometric capabilities to secure your "Vault" of financial data.
* **Processing:** Biometric authentication is handled entirely by your device's operating system.
* **No Access:** The App never has access to your actual face data or fingerprint data. We only receive a "Pass" or "Fail" signal from the operating system to unlock the App.

### C. Crash Logs and Stability (Firebase)
We use Google Firebase Crashlytics to help us identify crashes and fix bugs.
* **Data Collected:** If the App crashes, it may send an anonymous crash report containing technical details (e.g., "Crash occurred in DashboardScreen on iPhone 13, iOS 16").
* **Privacy:** This data is anonymous and does not contain your financial tokens or personal identity.
* [Google Privacy Policy](https://policies.google.com/privacy)

## 3. Data Retention & Deletion

* **Local Data:** For Platform Integrations (YouTube, etc.), uninstalling the App permanently deletes the data from your device.
* **Server Data (Banking):** If you choose to disconnect a bank account inside the App, we immediately **delete the associated Access Token from our server database**, permanently severing the connection to your bank.
* **Requesting Full Deletion:** You may request the deletion of all server-side data associated with your user ID by contacting us at the email below.

## 4. Third-Party Links
The App contains links to third-party websites (e.g., your Twitch Dashboard, Patreon Creator Page). We are not responsible for the privacy practices or content of these third-party sites.

## 5. Children’s Privacy
The App is not intended for children under the age of 13. We do not knowingly collect personal information from children under 13.

## 6. Your Consent
By using the App, you consent to our Privacy Policy.

## 7. Changes to This Policy
We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date at the top. You are advised to review this Privacy Policy periodically for any changes.

## 8. Contact Us
If you have questions regarding this privacy policy, you may contact us at:

* **Email:** hello@frncscccvl.com
* **Developer:** FRANCIS CACCAVALE
