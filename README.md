# 🔐 File Integrity Checker

A Python GUI-based File Integrity Checker that allows users to:

- 📂 Select a folder
- 📸 Create and update a **baseline snapshot**
- 🔍 Check for any file changes (modified, added, deleted)
- 📝 Generate integrity **reports**
- ♻️ Restore original files from backup

Built using **Tkinter**, **os**, and **pickle**, and compiled into a standalone `.exe` for Windows using `cx_Freeze`.

---

## 📁 Features

- **Baseline Creation** – Stores metadata of selected folder's structure and files.
- **Integrity Checking** – Compares current state to the saved baseline.
- **Detailed Reporting** – Saves a report of file modifications.
- **File Restoration** – Restores deleted/modified files using backup.
- **GUI Interface** – Easy-to-use interface built with Tkinter.

---

## 💾 Download Executable (Windows)

✅ You can run this tool on Windows without installing Python:

📥 [**Download File Integrity Checker (.zip)**](https://github.com/Mirinmano/File_integrity_checker/blob/master/File_Integrity_Checker.zip)

> Replace the link above with your actual ZIP file URL in GitHub Releases.

### How to Use (No Installation)

1. **Download** and **extract** the ZIP file.
2. Double-click `FileIntegrityChecker.exe` to launch the app.
3. Use the buttons to select a folder, create a baseline, check integrity, generate a report, or restore files.

⚠️ **Note:** Windows Defender may warn about running unsigned executables. Click **"More Info" → "Run Anyway"**.

---
