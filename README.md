# WFH Reporter — Downloads

Desktop app that automates the daily Work-From-Home report: it fills the monthly
Excel file, formats the Japanese date and email subject, and sends it — so you
only write the report content.

### ⬇ [Download the latest version](../../releases/latest)

| Platform | File | How to install |
| --- | --- | --- |
| **macOS** | `WFH-Reporter-mac.zip` | Unzip, move to **Applications**. First launch: **right-click → Open → Open** (the app is unsigned). |
| **Windows** | `WFH-Reporter-windows.zip` | Unzip, run **`WFH Reporter.exe`**. If SmartScreen warns: **More info → Run anyway**. |
| **Linux (Ubuntu)** | `WFH-Reporter-x86_64.AppImage` | `chmod +x WFH-Reporter-x86_64.AppImage`, then run it.<br>Ubuntu 22.04+ needs FUSE once: `sudo apt install libfuse2`.<br>Saving your password needs a keyring: `sudo apt install gnome-keyring`. |

On first run a short setup wizard asks for your profile and your OneOffice email
(the server and port are pre-filled). Your password is stored in your operating
system's keychain — never on disk.

---

This repository holds **built releases only**. The source code lives in a separate,
private repository.
