# Postrix Privacy Policy

**Last Updated:** 2026-02-19
**Effective Date:** 2026-02-19

Thank you for using Postrix. This Privacy Policy explains how the Postrix Chrome Extension (the "Extension") handles your information. Your privacy is critically important to us, and our policy is simple: **we do not collect your personal data.**

### 1. Information We Do Not Collect

The Extension is designed to work entirely on your local device. We **do not** collect, store, transmit, or have access to any of your personal information. This includes, but is not limited to:
- Your browsing history
- Your IP address
- Any text you enter into widgets (memos, checklists, etc.)
- Any personal identifiers

### 2. How Your Data is Stored

All data you create with the Extension (such as widgets, notes, links, and settings) is stored **exclusively on your own computer** using the browser's built-in `chrome.storage.local` API.

- Your data **never** leaves your device.
- Your data is **not** sent to any external servers.
- Only you can access your data.

### 3. Explanation of Required Permissions

The Extension requests certain permissions to function correctly. Here is a transparent explanation of why each one is needed:

-   **`storage` and `unlimitedStorage`**: These permissions are required to save all your widgets, notes, and settings locally on your computer. `unlimitedStorage` ensures you have enough space for all your content without hitting browser limits.
-   **`scripting` and `host_permissions: ["<all_urls>"]`**: To allow you to place widgets and interact with elements on any website you choose, the Extension needs permission to run its code (content scripts) on those pages. This permission is essential for the core functionality of Postrix. **We do not use this to track your browsing activity.** The code only runs to display your widgets and manage site-specific features.
-   **`activeTab`**: This provides a more limited, temporary permission to interact with the currently active website when you click the extension's icon or use a context menu item, ensuring minimal access is used when possible.
-   **`contextMenus`**: This allows us to add helpful shortcuts, like "New Memo," to the menu that appears when you right-click on a webpage.
-   **`alarms`**: This permission is used for the "Live Widget" feature. It allows the extension to periodically check for updates to the live content you've selected, even when you are not actively interacting with it.

### 4. Data Deletion

You are in complete control of your data. You can delete all data created by the Extension at any time by simply uninstalling the Extension from your Chrome browser. This will permanently remove all associated local storage.

### 5. Third-Party Services

The Extension does not use any third-party services, analytics trackers, or external APIs that would result in your data being shared.

### 6. Children's Privacy

The Extension does not knowingly collect any information from children under the age of 13. Since we do not collect any personal data at all, this applies to all users.

### 7. Changes to This Privacy Policy

If this policy changes in the future, we will provide a clear notification through the Extension's update notes on the Chrome Web Store page.

### 8. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us at: **[seojihan77@gmail.com]**
