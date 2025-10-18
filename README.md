# 🧰 UnixTools Assistant / Unlocker

A powerful Windows utility designed to **unlock**, **restore**, and **protect** your system from restrictions, malware policies, and suspicious activity.  
UnixTools Assistant combines administrative control, system recovery, and diagnostic tools into one elegant interface.

---

## 🔓 System Unlock

Unlock essential Windows features that may have been disabled by policies or malware:

- **Registry Editor Unlock** — Removes restrictions on accessing the Windows Registry Editor (`regedit`)
- **Task Manager Unlock** — Enables access to Windows Task Manager if it was disabled
- **Command Prompt Unlock** — Restores access to `CMD` and PowerShell
- **Control Panel Unlock** — Removes restrictions on accessing Control Panel
- **Run Dialog Unlock** — Re-enables the Windows Run dialog (`Win + R`)
- **Folder Options Unlock** — Restores access to Folder Options in Explorer
- **Context Menu Unlock** — Re-enables right-click context menus

---

## ⚙️ Task Manager

Advanced process and service management toolkit:

- **Process Management** — View all running processes (PID, name, memory usage, thread count)
- **Process Termination** — Kill individual processes or entire process trees
- **Process Suspension** — Freeze/unfreeze processes without killing them
- **Critical Process Protection** — Mark processes as *critical* or remove that status
- **Service Management** — View, start, stop, and delete Windows services
- **Real-time Search** — Instantly filter processes or services
- **Auto-refresh** — Updates every **3 seconds**

---

## 🚀 Startup Manager

Take full control of Windows startup behavior:

- **Registry Startup Items** — View/remove entries from `Run` and `RunOnce` keys
- **Winlogon Items** — Manage startup programs from Winlogon
- **Startup Folder** — View/manage startup folder items
- **Task Scheduler** — View and delete startup tasks
- **Search Functionality** — Search through all startup entries
- **Auto-refresh** — Updates every **5 seconds**

---

## 🛡 AntiGDI Protection

Real-time protection against GDI resource attacks (GDI bombs):

- **GDI Attack Detection** — Detects excessive GDI object creation
- **Automatic Window Blocking** — Closes suspicious windows automatically
- **Real-time Monitoring** — Tracks all windows and their GDI usage
- **Configurable Threshold** — Set a custom GDI object limit
- **Protection Toggle** — Enable or disable protection with one click

---

## 💾 MBR Backup & Restore

Safely backup and restore your system’s Master Boot Record (MBR):

- **MBR Backup** — Create a backup of the first 512 bytes of the selected disk  
- **MBR Restore** — Restore MBR from a backup file  
- **Disk Selection** — Choose which physical disk to manage  
- **Safety Checks** — Requires admin privileges for all operations  
- **Backup File Management** — Save and load `.mbr` backup files easily

---

## 🌐 HTTP Debugger (Network Monitor)

Monitor and analyze network activity in real-time:

- **Active Connections** — View all TCP connections instantly  
- **Process Identification** — See which process owns each connection  
- **Connection Details** — Local/remote IPs, ports, protocols, and states  
- **Suspicious Detection** — Automatically flags potential threats based on:
  - Suspicious ports (4444, 5555, 6666, 7777, 8888, 31337, etc.)
  - Processes running from temporary folders
  - Unknown processes connecting to external IPs
  - Excludes trusted system and browser processes  
- **Search & Filter** — Filter by process name, IP, or port  
- **Auto-refresh** — Updates every **2 seconds**

---

## 🛠 Advanced Tools

Essential recovery and system management features:

- **CMD/PowerShell Execution** — Run commands with administrator privileges  
- **Safe Mode Auto-Entry** — Boot automatically into Windows Safe Mode  
- **Safe Mode Disable** — Restore normal boot mode  
- **Drive Unhide** — Reveal drives hidden by policies or malware  
- **File Association Restore** — Repair broken `.exe` and other file types  
- **Audio Unblock** — Remove audio restrictions and restart sound service  
- **TopMost Window Bypass** — Disable “always on top” from all windows  
- **Mouse Unblock** — Restore mouse input if blocked  
- **HVNC Detection** — Detect hidden remote desktop sessions (hidden VNC)

---

## 🧩 Key Highlights

- 🪟 **All-in-One Windows Utility**
- 🧰 **Designed for Sysadmins and Security Analysts**
- ⚡ **Fast, lightweight, and portable**
- 🔐 **Focused on recovery, security, and control**

---

## ⚠️ Disclaimer

This tool is intended for **educational, administrative, and recovery purposes only**.  
Misuse on unauthorized systems is strictly prohibited.

---

## 📜 License

Distributed under the **MIT License**.  
See [`LICENSE`](./LICENSE) for more information.

---

### 💡 Developed with ❤️ by **UnixTools**
Empowering Windows administrators with smarter tools.
