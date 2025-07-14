# 📁 Smart File Organizer

Created with ❤️ by **Steven Techo**, a developer. : )

Smart File Organizer is an advanced desktop application for Windows that automates the organization of files, archives old ones, monitors folders in real time, and includes system monitoring, customizable rules, and a powerful admin panel — all packed into a clean GUI with system tray support.

---

## 🚀 Features

- 📂 Real-time file monitoring
- 🛡️ Optional virus scanning (via Windows Defender)
- 📁 Auto-sorting by file type using `folder_rules.json`
- 📦 Auto-archiving of old files (based on customizable days)
- 🧹 Automatic empty folder cleanup
- 🌙 Dark/Light mode toggle
- ⚙️ Admin Panel with:
  - Config editor (`folder_rules.json`)
  - System monitor (CPU, RAM, Disk, Temp)
  - Toggle logging & virus scan
- 🪟 System tray integration
- 🖥️ Auto-start on Windows boot
- 🧾 Activity log file
- 🎮 Special Minecraft `.jar` mod folder detection
- 🔧 Fully customizable settings

---

## 🖥️ Installation (for End Users)

### 🔸 Option 1: Run the App (No Installation Needed)

1. **Download the `SmartFileOrganizer.exe`** file.
2. **Double-click** to run.
3. The app will launch and sit in the **system tray**.
4. Use the GUI to:
   - Start/Stop monitoring
   - Browse folders
   - Customize rules in Admin Panel

> ✅ Python is **not required**. The app runs as a standalone executable.

---

### 🔸 Option 2: Set Up as a Startup App (Optional)

To enable auto-start on boot:

1. Open the app.
2. It will automatically register itself to **Windows Startup**.

---

## 🛠 Requirements

This app runs out of the box on most systems. If you encounter errors, ensure the following:

- ✅ Running **Windows 10/11 (64-bit)**
- ✅ You have **Visual C++ Redistributable 2015+** installed  
  [Download here](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist)

---

## ⚠️ Troubleshooting

- **“Windows protected your PC”**: Click *More info → Run anyway*
- **Missing icon in tray**: Make sure `icon.ico` is properly bundled or visible
- **Virus Scan not working**: Ensure Windows Defender is installed and enabled
- **SmartScreen warning**: This is expected for unsigned apps. You can safely continue.

---

## 📂 Config File Example (`folder_rules.json`)

```json
{
  "Documents": [".pdf", ".docx", ".txt"],
  "Images": [".jpg", ".png", ".gif"],
  "Videos": [".mp4", ".avi", ".mov"],
  "Music": [".mp3", ".wav", ".flac"],
  "Archives": [".zip", ".rar", ".7z"],
  "Installers": [".exe", ".msi"],
  "Scripts": [".py", ".js", ".sh"],
  "Others": []
}


** if you have bugs to be reported just email me here: louzingxiao@gmail.com :) **
