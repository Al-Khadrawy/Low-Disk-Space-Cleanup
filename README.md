# 🧹 Windows Disk Cleanup Utility

A lightweight Windows cleanup script designed to free disk space, remove unnecessary files, and improve overall system performance.

---

## 📌 Overview

This script automates common Windows cleanup tasks that are usually done manually or through multiple system tools.  
It is especially useful in **low disk space situations** or as part of **routine system maintenance**.

---

## ✨ Features

This script will:

- Stop optional background processes (if running)
- Clean system and user temporary files
- Remove Windows Update cache
- Clear browser cache (Internet Explorer & Google Chrome)
- Remove Windows Prefetch files
- Disable hibernation and delete `hiberfil.sys` (optional, if supported)

---

## 🔧 What the Script Does in Detail

### 🔹 Stops Optional Processes
Terminates non-essential processes to prevent file locking during cleanup operations.

### 🔹 Cleans Temporary & Cache Files
Deletes temporary files from:
- System Temp directories
- User Temp directories
- Cache locations

### 🔹 Clears Windows Update Cache
Removes downloaded Windows Update files that are no longer needed after installation.

### 🔹 Clears Browser Cache
Deletes cached data for:
- Internet Explorer
- Google Chrome

> ⚠️ Browser history, saved passwords, and bookmarks are **not affected**.

### 🔹 Removes Prefetch Files
Cleans Windows Prefetch files which may accumulate and consume unnecessary disk space over time.

### 🔹 Disables Hibernation (Optional)
Attempts to disable Windows hibernation and remove the `hiberfil.sys` file, which can free several gigabytes of disk space.

> ⚠️ Disabling hibernation will also disable **Fast Startup**.

---

## 🖥️ Requirements

- Windows 10 / Windows 11
- Administrator privileges
- Command Prompt (CMD) or PowerShell

---

## ▶️ How to Use

1. Download or clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
