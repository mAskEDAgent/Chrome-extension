# 📌 Leads Tracker Extension

A fully functional Google Chrome Extension designed to help users quickly save and manage web URLs. Built with vanilla web technologies, this tool leverages Chrome's native APIs and local storage to keep your important links organized across browsing sessions.

## ✨ Features
* **One-Click Tab Saving:** Uses the `chrome.tabs` API to instantly grab and save the URL of your currently active tab.
* **Manual Input:** Allows users to manually type or paste URLs into the input field for saving.
* **Persistent Data:** Utilizes the browser's `localStorage` to ensure your saved leads are never lost, even if you close the extension or restart your browser.
* **Safe Deletion:** Features a "double-click to delete" safety mechanism on the 'DELETE ALL' button to prevent accidental data erasure.
* **Clean UI:** A minimalist, lightweight popup interface designed specifically for extension constraints.

## 💻 Tech Stack
* **Language:** JavaScript (Vanilla), HTML5, CSS3.
* **APIs:** Chrome Extension Manifest V3, `chrome.tabs` API, Window `localStorage`.
* **Build Tool:** Vite.

## 🚀 How to Install & Run

Because this is a Chrome Extension, it runs directly in your browser rather than via a standard web server.

### Local Development (Vite)
If you want to edit the code and preview the UI:
1. Install dependencies: `npm install`
2. Start the dev server: `npm run dev`

### Installing the Extension in Chrome
To actually use the extension in your browser:
1. Open Google Chrome and navigate to `chrome://extensions/`.
2. Toggle **Developer mode** ON (top right corner).
3. Click **Load unpacked**.
4. Select the directory containing this project's `manifest.json` file.
5. The "Leads tracker" icon will now appear in your Chrome extensions menu!
