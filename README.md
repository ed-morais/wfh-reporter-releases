# WFH Reporter

A small desktop app that writes your daily Work-From-Home report for you — it
fills the monthly Excel form, formats the Japanese date and email subject, and
sends it. You just write what you worked on.

Works on **macOS, Windows, and Linux**. Available in **English and 日本語**.

---

## 1. Download

### ⬇ **[Download the latest version](../../releases/latest)**

Pick the file for your computer:

| Your computer | Download this file |
| --- | --- |
| 🍎 **Mac** | `WFH-Reporter.dmg` |
| 🪟 **Windows** | `WFH-Reporter-Setup.exe` |
| 🐧 **Linux (Ubuntu)** | `WFH-Reporter-x86_64.AppImage` |

---

## 2. Install & open

The app is safe, but it isn't code-signed (that costs a yearly fee), so the
first time you open it your computer shows a caution. Here's the one-time step
to get past it on each system.

### 🍎 Mac
1. Double-click **`WFH-Reporter.dmg`**.
2. In the window that opens, **drag WFH Reporter onto the Applications folder.**
3. Open **Applications**, then **right-click** WFH Reporter → **Open** → **Open**
   again in the dialog. *(Just this first time — after that, open it normally.)*

> If you double-click instead of right-click that first time, macOS blocks it with
> "unidentified developer." Right-click → Open is the trick.

### 🪟 Windows
1. Double-click **`WFH-Reporter-Setup.exe`**.
2. If a blue **"Windows protected your PC"** box appears:
   **More info** → **Run anyway**. *(First time only.)*
3. Follow the short installer. It installs for **just you** (no admin needed) and
   adds a **WFH Reporter** shortcut to your Start Menu.
4. Launch it from the **Start Menu** like any other program.

> To remove it later: **Settings → Apps → Installed apps → WFH Reporter → Uninstall.**

### 🐧 Linux (Ubuntu)
1. Make the file runnable — right-click `WFH-Reporter-x86_64.AppImage` →
   **Properties** → **Permissions** → tick **"Allow executing file as program"**
   (or in a terminal: `chmod +x WFH-Reporter-x86_64.AppImage`).
2. Double-click it to run.

> **Two one-time bits on Ubuntu 22.04+**, if it doesn't start:
> - `sudo apt install libfuse2` (the runtime the AppImage needs)
> - `sudo apt install gnome-keyring` (so it can save your password securely)

---

## 3. First run — set up (about a minute)

A short wizard walks you through three screens:

1. **Your profile** — your name, department, and employee ID.
2. **Email account** — your **OneOffice email** and **password**. The server and
   port are already filled in. Click **Test Connection** to check it works.
3. **Defaults** — your usual work hours (already filled with 09:00–17:30), your
   project/fund code, and who your reports go **To** / **Cc**.

Your password is stored in your computer's secure keychain — **never on disk and
never sent anywhere except your mail login.** Your setup stays on your computer.

---

## 4. Sending a report

On the **Daily Report** screen: check the date, adjust your work hours if needed,
write what you did, then **Send Report**. That's it — the spreadsheet is filled
and emailed for you.

- **Save for later** keeps a draft you can finish and send from **History**.
- **Forgot a day?** Change the date at the top to backfill it.
- Reports are saved on your computer under **Documents → WFH Reporter**.

---

## 5. Staying up to date

When a newer version is out, an **"Update available"** button appears in the
sidebar — click it to come back here and download the new file. You can also
check any time in **Settings → About**.

## 6. Something wrong, or an idea?

Use the **Feedback** button in the app's sidebar (bug reports, questions, and
suggestions all welcome), or email **edilson@atr.jp** directly.

---

*This page has the downloads only. If it won't open, re-check the one-time step
in section 2 for your system.*
