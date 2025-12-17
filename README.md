# 🧹 Windows Disk Cleanup Utility

![Windows](https://img.shields.io/badge/OS-Windows%2010%20%7C%2011-blue)
![CMD](https://img.shields.io/badge/Script-CMD%20%7C%20Batch-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A lightweight Windows cleanup script designed to free disk space, remove unnecessary files, and improve overall system performance.

---

## 📸 Screenshot  
<img width="958" height="878" alt="2025-10-19 01_47_11-NVIDIA GeForce Overlay" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj3w183qLbWa6nDMJN8YQ4aU16MNODsc1oaemyQ_KC40ZP1WBFjbi9zl9CGfD9TvzTSgPMOOShyphenhyphenb10zAbm-xhl6y3HxQMS8iRJRbdz4v7XzExVfZcOMvO0ePuPCSpLXGMTWNYn7WrIF3dX6_KK3wvRWYUZw7HLhejHTGPHI-q6YVUHmXhSz_BOpmvEfNN70/s763/3.png" />


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

## 📜 Credits  

This release (**1.0.0**) was fully contributed by **[AL KHADRAWY](https://github.com/Al-Khadrawy/Low-Disk-Space-Cleanup/releases/tag/1.0.0)**.  
All new features, fixes, and improvements are thanks to his work. 

---

## 📜 License  

MIT License

Copyright (c) 2025 AL Khadrawy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
