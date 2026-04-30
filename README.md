# Monitor Dimmer

A lightweight Windows utility that allows you to control your monitor brightness using a software overlay.

This is especially useful for monitors that **do not support DDC/CI brightness control**, or when brightness control apps simply don’t work reliably.

---

## ✨ Features

- 🔆 Adjust brightness using an overlay (no hardware support required)
- 🖥️ Multi-monitor support
- 🔄 Sync all monitors or control them independently
- 🎛️ Clean tray-based UI
- ⌨️ Global hotkeys:
  - `Ctrl + PgUp` → Increase brightness  
  - `Ctrl + PgDn` → Decrease brightness  
- 🚀 Start with Windows option
- 🎮 Works over most applications (including many games)

---

## ⚙️ How It Works

Instead of controlling your monitor hardware directly, this app creates a **transparent overlay** on top of your screen and adjusts its opacity to simulate brightness changes.

This makes it compatible with virtually any monitor — even those that don’t support brightness control via software.

---

## ⚠️ Important Notes

Many applications (especially games, elevated/admin apps, and browsers) run with higher privileges than normal applications.

In those cases, the overlay may not appear on top.

### ✅ Solution

Run the app as Administrator:

1. Right-click `MonitorDimmer.exe`
2. Click **Run as administrator**

---

## 🚀 Optional: Run as Administrator on Startup (No UAC Prompt)

If you want the app to:
- start automatically
- run as admin
- avoid UAC popups

Use Task Scheduler:

1. Open **Task Scheduler**
2. Click **Create Task**
3. In **General**:
   - Name: `MonitorDimmer`
   - Enable **Run with highest privileges**
4. In **Triggers**:
   - Add → **At log on**
5. In **Actions**:
   - Program: path to `MonitorDimmer.exe`
6. Save

---

## 📦 Download

Download the latest version from the [Releases](../../releases) section.

---

## 🖼️ Screenshots

_Add a screenshot here of your tray popup UI_

---

## 🧠 Why This Exists

Many monitors (especially cheaper or older ones) do not support DDC/CI, or have broken implementations.

This app provides a simple, reliable workaround using a software-based approach.

---

## ⚠️ Limitations

- Does not affect:
  - UAC prompts
  - Lock screen
  - Some exclusive fullscreen applications
- Slight visual dimming only (not true hardware brightness)

---

## 📄 License

MIT License (or whatever you choose)

---

## 💬 Feedback

Feel free to open issues or suggest improvements.
