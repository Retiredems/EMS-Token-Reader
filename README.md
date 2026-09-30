<div align="center">

# 📬 EMS Token Reader

### Desktop mailbox reader powered by your own access tokens

**Access any Microsoft 365 mailbox directly — no OAuth setup, no browser redirects. Just paste your token and read.**

![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-Private-red?style=flat)

</div>

---

## What Is EMS Token Reader?

EMS Token Reader is a standalone desktop application that lets you access and manage any Microsoft 365 mailbox using an access token directly — without going through a traditional OAuth browser flow. Designed for power users and professionals who already have access tokens and need a clean, full-featured email client to work with them.

Import a token, save multiple account profiles, and get full mailbox access instantly. Everything is local — your tokens are stored securely on your own device.

---

## Screenshots

<!-- Add screenshots here -->

---

## How Token Access Works

| Layer | What It Does |
|---|---|
| **Token Import** | Paste any valid Microsoft Graph access token to authenticate instantly |
| **Token Preview** | App decodes the token locally to show the account email, name, and expiry time before connecting |
| **Auto-Refresh** | Optionally provide a refresh token — the app silently renews access before it expires |
| **Saved Profiles** | Store multiple token profiles locally; switch between accounts with one click |
| **Expiry Alerts** | Token cards clearly show expiry status — valid, expiring soon, or expired |
| **Secure Storage** | Tokens are stored in your platform's standard app data folder, never transmitted |

---

## Mailbox Features

| Feature | Details |
|---|---|
| **Folder Tree** | Full folder list with unread counts — Inbox, Sent, Drafts, Deleted, Junk, and all custom folders |
| **Message List** | Paginated list (50 per page) with colored sender avatars, unread indicators, subjects, and snippets |
| **HTML Reader** | Full HTML email rendering with inline styles, images, and attachments |
| **Search** | Search across the entire mailbox with instant results |
| **Compose** | Write new emails with To, Cc, Bcc, Subject, and rich text body |
| **Reply / Reply All** | Reply with quoted context preserved |
| **Forward** | Forward messages to any recipient |
| **Delete** | Move messages to Deleted Items with confirmation |
| **Move to Folder** | Move any message to any folder in your mailbox |
| **Mark Read / Unread** | Toggle read status on any message |
| **Attachments** | View attachment list and download files to your local machine |
| **Export CSV** | Export the current message list to a CSV file for external processing |
| **Auto Mark Read** | Messages are marked as read automatically when opened |

---

## Key Features

### Token Management
- Import by pasting an access token — no app registration required
- Preview decoded token info (email, name, expiry) before connecting
- Save profiles with a custom label for quick access
- Refresh tokens silently when available
- Delete saved profiles at any time

### Full Email Client
- Three-pane layout: folders / message list / reader
- Colored avatar circles for visual sender identification
- Bold unread styling with blue accent indicators
- Pagination for large mailboxes (50 messages per page)
- Full HTML email body rendering

### Built for Power Users
- Works with any valid Microsoft Graph access token
- Supports FOCI token refresh (multiple Microsoft client IDs attempted)
- Stores token profiles per-device in your app data folder
- Clean Fluent UI design matching Microsoft 365 aesthetics

---

## Installation

### Windows
1. Download `EMS-Token-Reader-Setup.exe` from the latest release
2. Run the installer (no admin required — installs per-user)
3. Launch **EMS Token Reader** from the Start Menu or Desktop

### macOS
1. Download `EMS_Token_Reader_macOS.zip` from the latest release
2. Unzip and drag **EMS Token Reader.app** to your Applications folder
3. Right-click → Open the first time (to bypass Gatekeeper)

---

## Getting a License

EMS Token Reader is a paid tool available from the EMS Tools suite.

**Contact via Telegram:** [@Retiredems](https://t.me/Retiredems)

| Plan | Price | Machines |
|---|---|---|
| Lifetime License | $100 | Up to 3 PCs |

---

## How to Get a License Key

1. Launch the app — it will display your **Hardware ID (HWID)**
2. Send your HWID to [@Retiredems](https://t.me/Retiredems) on Telegram
3. Complete payment
4. Enter your license key in the app to activate

---

## Getting a Token

EMS Token Reader works with any valid Microsoft Graph access token scoped to `Mail.Read`, `Mail.ReadWrite`, `Mail.Send`, or similar mail permissions.

Tokens can be obtained through the EMS sign-in tools or any standard Microsoft OAuth device code flow targeting the Microsoft Graph API.

---

## Token Storage Location

| Platform | Location |
|---|---|
| Windows | `%APPDATA%\EMS\TokenReader\tokens.json` |
| macOS | `~/Library/Application Support/EMS/TokenReader/tokens.json` |
| Linux | `~/.config/EMS/TokenReader/tokens.json` |

Tokens are stored in plain JSON on your local machine. Keep this file secure.

---

## System Requirements

| | Minimum |
|---|---|
| **OS** | Windows 10 64-bit · macOS 12+ |
| **RAM** | 256 MB |
| **Disk** | 300 MB |
| **Network** | Required for mailbox access |
| **Account** | Any Microsoft 365 / Outlook account with a valid access token |

---

## Changelog

### v1.0.0
- Initial release
- Token import with live JWT preview (email, name, expiry)
- Saved token profiles with auto-refresh support
- Full folder tree with unread counts
- Paginated message list with colored sender avatars
- HTML message reader
- Compose, Reply, Reply All, Forward
- Delete, Move to folder, Mark read/unread
- Search across mailbox
- Attachment download
- Export to CSV

---

## Other EMS Tools

| Tool | Description |
|---|---|
| [EMS Mailer](https://github.com/Retiredems/EMS-Mailer) | Bulk email sender with template support |
| [EMS Email Sorter](https://github.com/Retiredems/EMS-Email-Sorter) | Sort and categorize large email lists |
| [EMS Email Verifier](https://github.com/Retiredems/EMS-Email-Verifier) | Verify email deliverability at scale |
| [EMS Token Reader](https://github.com/Retiredems/EMS-Token-Reader) | This tool |

---

## Support

- **GitHub Issues:** [Open an issue](https://github.com/Retiredems/EMS-Token-Reader/issues)
- **Telegram:** [@Retiredems](https://t.me/Retiredems)

---

<div align="center">

Built with precision by **Retiredems** · Powered by PyQt6

</div>
