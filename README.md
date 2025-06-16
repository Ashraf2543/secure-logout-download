# Secure Logout Download Extension

A simple Chrome extension that identifies logout links/buttons on any webpage and helps users log out securely.

## 🛡️ Features

- Automatically detects logout buttons/links.
- Provides a quick way to navigate to logout pages.
- Supports scanning current web pages for common logout patterns.
- Useful for security-conscious users, shared systems, or public access terminals.

## 📁 Project Structure

```
secure-logout-download/
├── assets/
│   └── icon.png              # Extension icon
├── background.js             # Background script for extension
├── content.js                # Script that scans pages for logout links
├── manifest.json             # Chrome extension config file
├── popup.html                # Extension popup UI
└── popup.js                  # Script to handle popup behavior
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Ashraf2543/secure-logout-download.git
cd secure-logout-download
```

### 2. Load Extension in Chrome

1. Open Chrome and go to `chrome://extensions/`
2. Enable **Developer Mode** (top-right corner)
3. Click **Load Unpacked**
4. Select the project folder (`secure-logout-download/`)

### 3. Use the Extension

- Click the extension icon in your Chrome toolbar.
- It will scan the current page for logout links/buttons.
- Click the highlighted results to log out.

## 🔒 Why Use This?

In shared or public systems, users often forget to log out. This extension helps by:

- Making logout options easier to find
- Assisting in secure browsing habits
- Helping automate logout detection for developers or testers

## 📸 Screenshots

*![image](https://github.com/user-attachments/assets/ba771ddc-6ffa-41ac-85a7-648bf9f0c94d)
*

## 📜 License

This project is licensed under the License. See the [LICENSE](LICENSE) file for details.

---

### 👤 Author

**[Ashraf2543](https://github.com/Ashraf2543)**
