# 🧾 Bill Snap – Privacy Policy

**Last Updated:** May 2026

Welcome to **Bill Snap**. Your privacy is important to us. This Privacy Policy explains how your information is collected, used, stored, and protected when using the Bill Snap Android application.

---

## 📌 About Bill Snap

Bill Snap is an **offline-first** expense tracker and bill scanning Android application that helps users:

- 📸 Scan receipts and bills using the device camera (with optional AI extraction)
- ✍️ Manually add expenses and transactions
- 💰 Track expenses with 19+ built-in categories plus custom categories
- 📊 View analytics, monthly trends, and category breakdowns
- 🎯 Set monthly category budgets with overspend alerts
- 📦 Backup, restore, and export data as PDF or Excel

---

## 📂 Information We Collect

Bill Snap is designed so that **your personal financial data stays on your device**. We do not operate a server, and we do not collect, transmit, or sell your bills, receipts, or analytics to anyone.

### 📷 Bill Images
When you scan or upload a bill, the app may process:
- The bill image (stored locally on your device)
- OCR text extracted on-device
- Extracted bill information (shop name, items, prices, totals, date)

### 🧾 Expense Information (stored locally)
- Shop names, addresses, dates
- Items, quantities, prices, discounts
- Categories (built-in or custom)
- Payment methods (cash / card / online)
- Bill totals and final amounts
- Monthly category budgets

### ⚙️ App Settings (stored locally)
- Selected currency
- Theme preference (light / dark / system)
- Custom categories you create
- Anthropic API key (if you choose to use AI extraction)
- Onboarding and tutorial completion flags

---

## 🤖 AI Processing (Optional)

AI bill extraction is **optional**. If — and only if — you provide your own Anthropic API key, the app will send the bill image to Anthropic's Claude API to extract structured data (shop name, items, totals, etc.).

- **AI provider used:** Anthropic Claude
- **What is sent:** the bill image and a system prompt asking the model to return structured JSON
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

## 💾 Data Storage

Bill Snap stores all your data **locally on your device**.

We do **not** operate any cloud server. We do **not** synchronise your data across devices. We do **not** maintain user accounts.

---

## 📦 Backup & Restore

The app allows you to:
- Create a local backup file containing all bills, categories, and budgets
- Restore data from a backup file
- Transfer data between your own devices using a backup file

You are solely responsible for the security of any backup file you create, share, or move outside the app.

---

## 📤 Export Reports

You may export your bill history as **PDF** or **Excel (.xlsx)** files for your own records. These files are saved to your device's Downloads folder. The app does not transmit exported files to any server.

---

## 📱 Permissions Used

| Permission | Purpose |
|---|---|
| 📷 **Camera** | Required to scan bills with the camera |
| 🖼️ **Photo Library / Media Images** | Required to select existing bill images from your gallery |
| 📁 **Storage / Downloads** | Required to save backups and PDF/Excel exports to Downloads |
| 🌐 **Internet** | Required only for AI extraction (if enabled) |

The app requests permissions only when needed and explains the reason.

---

## 🔒 Security

We take reasonable measures to protect your data while it is on your device. However, no method of electronic storage is completely secure. We cannot guarantee absolute security.

You can enhance your privacy by:
- Using device-level encryption (default on modern Android)
- Setting a screen lock
- Storing backup files in a secure location

---

## 🔄 Changes to This Policy

We may update this Privacy Policy from time to time to reflect changes to our app or to applicable laws. The "Last Updated" date at the top of this document indicates when the policy was last revised. Continued use of the app after changes are posted constitutes acceptance of the updated policy.

---

## 📧 Contact

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

📩 **cameounix@gmail.com**

---

## ✅ Summary

- 🏠 **Your data stays on your device** — bills, items, and budgets are stored locally
- 🚫 **No cloud account required** — we don't operate servers and don't collect your financial data
- 🤖 **AI is optional** — you bring your own Anthropic API key, or use the offline rule-based parser
- 📦 **You control your backups** — create, share, or delete backup files at your discretion
- 🔐 **Your API key stays local** — never transmitted to us

Thank you for using Bill Snap ❤️
