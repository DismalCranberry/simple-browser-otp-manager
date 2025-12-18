# What is this?
Welcome to your very own OTP sidekick! 🕵️‍♂️🔐 This extension generates 6-digit TOTP codes and stores your secrets locally so you can grab a fresh code whenever you need it. No more fumbling for your phone—everything you need is right in your browser!

# How It Works
Imagine you have a squad of five little helpers:

**Secret Keeper** 📌 – Safely stashes all your Base32 secrets in Chrome storage.
**Code Maker** ⏱️ – Uses those secrets to whip up new TOTP codes every 30 seconds.
**Clipboard Hero** 📋 – Copies a code with a click and shows a tiny “Copied!” message so you know it worked.
**Organizer** 🗂️ – Lets you rename, delete, and drag to reorder your accounts.
**Timer** ⏳ – Counts down the seconds and refreshes the codes right on schedule.

Together they let you:

- 📜 Store multiple secrets
- 🔄 Refresh and display codes automatically
- 👀 Copy codes to the clipboard
- 💼 Manage your list with rename, delete, and drag-and-drop

# File Structure
- **manifest.json**: Chrome extension manifest
- **popup.html**: Main popup UI
- **popup.js**: Logic for secrets, code generation, and UI interactions
- **RandomCat.png**: Cute icon for the extension

# Getting Started

Load the **OTP_EXT** directory as an unpacked extension in Chrome. Open the popup, add your Base32 secrets, and start generating TOTPs.

Enjoy convenient two-factor codes! 🚀
