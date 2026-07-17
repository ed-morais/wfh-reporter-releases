# WFH Reporter

A desktop app that writes your daily Work-From-Home report: it fills the monthly
Excel form, formats the Japanese date and email subject, and sends the email. You
write what you worked on.

Runs on macOS, Windows, and Linux. English and 日本語.

## Download

[Download the latest version.](../../releases/latest)

| System | File |
| --- | --- |
| Mac | `WFH-Reporter.dmg` |
| Windows | `WFH-Reporter-Setup.exe` |
| Ubuntu | `wfh-reporter_<version>_amd64.deb` |
| Other Linux | `WFH-Reporter-x86_64.AppImage` |

The app is not code-signed, so the first launch shows a one-time warning on Mac
and Windows. The steps below get past it.

## Install

### Mac
1. Open `WFH-Reporter.dmg`.
2. Drag WFH Reporter onto the Applications folder.
3. In Applications, right-click WFH Reporter and choose Open, then Open again.
   Do this the first time only; after that, double-click as usual.

Double-clicking the first time gives an "unidentified developer" error. Right-click
then Open avoids it.

### Windows
1. Run `WFH-Reporter-Setup.exe`.
2. If a "Windows protected your PC" box appears, click More info, then Run anyway.
3. Complete the installer. It installs for the current user (no admin needed) and
   adds a Start Menu shortcut.

Uninstall from Settings > Apps > Installed apps > WFH Reporter.

### Ubuntu (.deb)
Install from a terminal in the download folder:

```bash
sudo apt install ./wfh-reporter_*_amd64.deb
```

Then launch WFH Reporter from the applications menu. Uninstall with
`sudo apt remove wfh-reporter`.

Double-clicking the `.deb` may also work, but on recent Ubuntu the terminal command
is more reliable.

### Other Linux (AppImage)
1. Make it executable: `chmod +x WFH-Reporter-x86_64.AppImage` (or right-click >
   Properties > Permissions > Allow executing file as program).
2. Double-click to run. Nothing is installed.

On Ubuntu 22.04+ the AppImage needs `libfuse2` (`sudo apt install libfuse2`), and
`gnome-keyring` to store the password (`sudo apt install gnome-keyring`).

## First run

A short setup covers three screens:

1. Profile: name, department, employee ID.
2. Email account: OneOffice email and password. The server and port are pre-filled.
   Use Test Connection to check them.
3. Defaults: work hours (pre-filled 09:00-17:30), project/fund code, and the To/Cc
   recipients.

The password is stored in the operating system keychain, not on disk, and is only
sent to your mail login. Setup stays on your computer.

## Sending a report

On the Daily Report screen, check the date, adjust the hours if needed, write what
you did, and click Send Report. The spreadsheet is filled and emailed.

- Save for later keeps a draft you can finish from History.
- Change the date at the top to backfill a missed day.
- Reports are saved under Documents/WFH Reporter.

## Updates

When a newer version is available, an "Update available" button appears in the
sidebar and links back here. You can also check under Settings > About.

## Feedback

Use the Feedback button in the sidebar, or email edilson@atr.jp.
