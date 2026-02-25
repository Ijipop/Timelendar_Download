# Timelendar

Desktop collaborative calendar application (private project). **No installation**: the software runs standalone, ready to use.  
*[Français](README.md)*

## Editions: Free and Pro

Timelendar is available in **two editions**:

| | **Free** | **Pro (paid)** |
|---|----------|----------------|
| Calendar & timeline | ✅ | ✅ |
| Local events, todo, backups | ✅ | ✅ |
| User account (Supabase) | ❌ | ✅ |
| Shared workspaces & sync | ❌ | ✅ |
| CalDAV / iCloud / Outlook connection | ❌ | ✅ |
| Data tab (export, etc.) | ❌ | ✅ |
| Animated title (Pro branding) | ❌ | ✅ |

**Free edition**: local use, no account. Data stays on your machine.

**Pro edition (paid)**: account, shared calendars, real-time sync, CalDAV/iCloud and **Outlook calendar sync**. **The Pro version will be available soon**; you can try the Free edition in the meantime.

When you **subscribe**, a link to download the Pro version will be provided to you.

### Building each edition

```bash
npm run tauri:build:free   # Free
npm run tauri:build:full   # Pro
```

---

## Features

- 📅 **Calendar**: month, week and year views; create and edit events
- 📊 **Timeline**: blocks and rows by week, multiple tabs, drag-and-drop, resizing
- ✏️ **Events**: recurrence (daily to yearly), quick edit, send between calendar and timeline
- 📌 **Deadlines**: due dates visible on the timeline and in events
- 📋 **Todo list** built into the header
- 💾 **Backup and restore**: export/import workspace backup (.json file)
- 🎨 **Wide color versatility**: palettes (Classic, Duo, Timelendar…), light/dark mode, per-calendar colors
- 👥 **Pro**: shared workspaces, real-time sync, invites and roles (owner, admin, member, viewer), CalDAV/iCloud and **Outlook calendars**
- 📡 **Offline mode**: use without connection; sync on reconnect (Pro)
- 🌐 **Bilingual**: French and English
- 🖥️ Native desktop app (Windows + macOS)

---

## Code signing and security warnings (Windows / Mac)

The application **is not signed**: we do not have a code-signing certificate (paid license). On **Windows** and **macOS**, antivirus or the system may therefore show a security warning on first launch.

**It is not dangerous.** The software is safe; it is simply not yet profitable enough to justify the cost of a signing certificate. We prefer to be transparent about this.

To see **how to work around** this warning and install/run the app with confidence, refer to **README.txt** provided with the application or in the repo.

Private project – all rights reserved.
