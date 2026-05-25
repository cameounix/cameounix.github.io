# 🧾 Bill Snap – Privacy Policy

**Last Updated:** 25 May 2026
**App Version:** 1.3.1

Welcome to **Bill Snap**. Your privacy is important to us. This Privacy Policy explains how your information is collected, used, stored, and protected when using the Bill Snap Android application.

---

## 📌 About Bill Snap

Bill Snap is an **offline-first** expense tracker and bill scanning Android application that helps users:

- 📸 Scan receipts and bills using the device camera (with optional AI extraction)
- 📄 Import bills as PDF or Excel (.xlsx / .xls) files
- ✍️ Manually add expenses and transactions
- ⚡ Re-use repeat transactions via Instant Transaction templates
- 💰 Track expenses with 19+ built-in categories plus custom categories
- 📊 View analytics, monthly trends, and category breakdowns
- 🎯 Set monthly category budgets with overspend alerts
- 📋 Track recurring monthly needs that auto-reset each month
- 📦 Backup, restore, and export data as PDF or Excel

---

## 📂 Information We Collect

Bill Snap is designed so that **your personal financial data stays on your device**. We do not operate a server, and we do not collect, transmit, or sell your bills, receipts, or analytics to anyone.

### 📷 Bill Images, PDFs, and Spreadsheets
When you scan or upload a bill, the app may process:
- The bill image, PDF, or Excel file (stored locally on your device)
- OCR text extracted on-device (Android only, via Google ML Kit)
- Extracted bill information (shop name, items, prices, totals, date)

### 🧾 Expense Information (stored locally)
- Shop names, addresses, dates
- Items, quantities, prices, discounts
- Categories (built-in or custom)
- Payment methods (cash / card / online)
- Bill totals and final amounts
- Monthly category budgets
- Monthly needs (recurring items)
- Instant transaction templates

### ⚙️ App Settings (stored locally)
- Selected currency
- Theme preference (light / dark / system)
- Custom categories you create
- Anthropic API key (if you choose to use AI extraction)
- Onboarding and tutorial completion flags

---

## 🤖 AI Processing (Optional)

AI bill extraction is **optional**. If — and only if — you provide your own Anthropic API key, the app will send the scanned content to Anthropic's Claude API to extract structured data (shop name, items, totals, etc.).

- **AI provider used:** Anthropic Claude (`claude-sonnet-4-6` for extraction, `claude-haiku-4-5` for API key verification)
- **What is sent:** the bill image, PDF, or Excel text and a system prompt asking the model to return structured JSON
- **What is NOT sent:** your other bills, history, analytics, or any personal account information
- **When AI is disabled or unavailable:** the app falls back to an on-device rule-based parser. No data leaves your device in this case.

If you do not enter an API key, AI extraction is fully disabled and the app operates in 100% offline mode for scanning.

Anthropic's privacy practices apply to data sent to their API:
👉 https://www.anthropic.com/legal/privacy

---

## 🔐 API Keys

Your AI API key:
- Is stored **locally on your device**
- Is **never** transmitted to us or any third party other than Anthropic when you initiate an AI extraction
- Can be removed at any time from the **AI Setting** screen

---

## 📢 Advertising (Google AdMob)

Bill Snap shows occasional interstitial ads served by **Google AdMob** to support continued development of the app.

- **Ad provider:** Google AdMob
- **Ad format:** Interstitial (full-screen ads shown after every 5th manual transaction save and every 3rd scanned bill save)
- **What AdMob may collect:** an advertising identifier, approximate location derived from IP address, and standard ad-request signals to serve and measure ads. Bill Snap itself does not read or transmit your bills to AdMob.

Google's advertising and privacy practices apply:
👉 https://policies.google.com/technologies/ads
👉 https://policies.google.com/privacy

You can reset or limit your advertising ID in your Android device's **Settings → Privacy → Ads**.

---

## ⭐ In-App Review (Google Play)

When you tap **Rate Us** in the Contact & Feedback screen, the app uses the **Google Play In-App Review API** to show the native rating prompt. The review flow is handled entirely by Google Play and is governed by Google's Privacy Policy. Bill Snap does not see or store your rating or review text.

If in-app review is not available on your device, the app opens the Bill Snap listing on the Play Store instead.

---

## 📧 Device Information for Support Emails

When you tap **Contact Support**, **Report a Bug**, or **Feature Request** in the Contact & Feedback screen, the app pre-fills the outgoing email with the following diagnostic information so we can help you faster:

- App name, version, build number, and package name
- Android version and SDK level
- Device manufacturer and model

This information is **only** placed into the body of the email draft on your device. Nothing is collected or transmitted automatically — you choose whether to send the email, and you can edit or delete any of the diagnostic information before sending.

---

## 💾 Data Storage

Bill Snap stores all your data **locally on your device** using an on-device SQLite database and Android `SharedPreferences`.

We do **not** operate any cloud server. We do **not** synchronise your data across devices. We do **not** maintain user accounts.

---

## 📦 Backup & Restore

The app allows you to:
- Create a local `.bsnap` backup file containing all bills, categories, budgets, monthly needs, instant transaction templates, currency, and theme settings
- Restore data from a backup file (with **Merge** or **Overwrite** modes)
- Transfer data between your own devices using a backup file

You are solely responsible for the security of any backup file you create, share, or move outside the app.

---

## 📤 Export Reports

You may export your bill history as **PDF** or **Excel (.xlsx)** files for your own records. These files are saved to your device's Downloads folder via Android `MediaStore`. The app does not transmit exported files to any server.

---

## 🔗 Opening External Links

Some buttons open URLs in your browser or other apps (e.g. **Privacy Policy**, **Terms**, **Rate Us → Play Store**, **Contact Support → email client**, **Share App → share sheet**). These are standard Android intents handled by other apps on your device; Bill Snap does not record which links you open.

---

## 📱 Permissions Used

| Permission | Purpose |
|---|---|
| 📷 **Camera** | Required to scan bills with the camera |
| 🖼️ **Photo Picker / Files** | To select existing bill images, PDFs, or Excel files. Uses the Android Photo Picker / Storage Access Framework — no broad media permission is requested. |
| 📁 **Storage / Downloads** | To save backups and PDF/Excel exports to the Downloads folder via MediaStore. The legacy `WRITE_EXTERNAL_STORAGE` permission is only declared for Android 9 and below. |
| 🌐 **Internet** | Required only for: (a) AI extraction when you opt in by providing an API key, (b) serving Google AdMob ads, and (c) opening Play Store / in-app review / external links. |

The app requests permissions only when needed and explains the reason.

---

## 🔒 Security

We take reasonable measures to protect your data while it is on your device. However, no method of electronic storage is completely secure. We cannot guarantee absolute security.

You can enhance your privacy by:
- Using device-level encryption (default on modern Android)
- Setting a screen lock
- Storing backup files in a secure location

---

## 👶 Children's Privacy

Bill Snap is not directed at children under 13 and we do not knowingly collect any personal information from children. If you believe a child has provided us with information, please contact us so it can be deleted.

---

## 🔄 Changes to This Policy

We may update this Privacy Policy from time to time to reflect changes to our app or to applicable laws. The "Last Updated" date at the top of this document indicates when the policy was last revised. Continued use of the app after changes are posted constitutes acceptance of the updated policy.

---

## 📧 Contact

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

📩 **cameounix@gmail.com**

---

## ✅ Summary

- 🏠 **Your data stays on your device** — bills, items, budgets, monthly needs, and templates are stored locally
- 🚫 **No cloud account required** — we don't operate servers and don't collect your financial data
- 🤖 **AI is optional** — you bring your own Anthropic API key, or use the offline rule-based parser
- 📢 **Ads via Google AdMob** — see Google's ad policies for details; you can reset your ad ID in Android settings
- ⭐ **Ratings via Google Play** — in-app review is handled entirely by Google Play
- 📧 **Support emails include diagnostic info** — pre-filled locally, never auto-sent
- 📦 **You control your backups** — create, share, restore, or delete backup files at your discretion
- 🔐 **Your API key stays local** — never transmitted to us

Thank you for using Bill Snap ❤️
