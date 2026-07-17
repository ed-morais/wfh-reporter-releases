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
| **Mac** | `WFH-Reporter-mac.zip` |
| **Windows** | `WFH-Reporter-windows.zip` |
| **Linux (Ubuntu)** | `WFH-Reporter-x86_64.AppImage` |

---

## 2. Install & open

The app is safe, but it isn't code-signed (that costs a yearly fee), so the
first time you open it your computer shows a caution. Here's the one-time step
to get past it on each system.

### Mac
1. Double-click `WFH-Reporter-mac.zip` to unzip it.
2. Drag **WFH Reporter** into your **Applications** folder.
3. **Right-click** it → **Open** → **Open** again in the dialog.
   *(Just this first time — after that, open it normally.)*

> If you double-click instead of right-click, macOS blocks it with
> "unidentified developer." Right-click → Open is the trick.

### Windows
1. Right-click `WFH-Reporter-windows.zip` → **Extract All**.
2. Open the extracted folder and double-click **`WFH Reporter.exe`**.
3. If a blue **"Windows protected your PC"** box appears:
   **More info** → **Run anyway**. *(First time only.)*

> Keep the whole folder together — the `.exe` needs the files next to it.

### Linux (Ubuntu)
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
suggestions all welcome).

---

*This page has the downloads only.*
