# Privacy Policy for Echo

**Last Updated:** February 20, 2026

Echo ("the Extension") is a developer-focused Chrome extension for request interception and mocking. This policy explains how Echo handles your information. **We do not collect, sell, or share your data.**

---

## 1. No Personal Data Collection

Echo **does not** collect, store, or transmit any of the following to external servers or third parties:

- Personal information  
- Browsing history  
- Network traffic or request/response content  
- Analytics or usage data  

All processing described below happens **only on your device**.

---

## 2. How Echo Uses Data Locally

### Network request interception

Echo intercepts network requests (e.g. `fetch` and XHR) **only** to apply your own rules (mocking, patching, or other modifications). This is done entirely in your browser; no request data is sent elsewhere.

### Local storage

Your rules and configuration are stored **only** on your machine using:

- **IndexedDB** and **chrome.storage** (browser storage)

We do not have access to this data. It remains under your control and stays on your device.

---

## 3. Why We Request Permissions

| Permission        | Purpose |
|-------------------|--------|
| **Host permissions** | To inject the logic needed for request interception on the pages you choose. Echo does not monitor or record general browsing activity. |
| **Storage**       | To save your settings and mock rules (e.g. globally or per site). |

Permissions are used only for these developer-tool features, not for tracking or analytics.

---

## 4. Third-Party Services

Echo does **not** integrate with third-party analytics, tracking, or advertising. The extension works offline and does not send data to any external service.

---

## 5. Your Control and Data Retention

- Your rules and settings stay in your browser until you change or remove them.  
- Uninstalling the extension removes data stored by Echo (subject to your browser’s storage behavior).  
- We do not retain any copy of your data because we never receive it.

---

## 6. Changes to This Policy

We may update this privacy policy from time to time. The "Last Updated" date at the top will reflect the latest version. Continued use of Echo after changes means you accept the updated policy.

---

## 7. Contact

Questions about this policy or Echo’s privacy practices:

- **Email:** slogllykop07@gmail.com  
- **GitHub:** Open an issue on the Echo repository  

---

*Echo is built for developers who need local control over network requests. Your data stays on your device.*
