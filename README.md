# 🎮 Virtual Play Server - Installation & Setup Guide

Turn your Android phone into a powerful game controller for your PC!  
This server runs on your Windows PC and communicates with the **Virtual Gamepad** Android app to emulate an Xbox 360 controller in real time using **ViGEm**.

---

## 📦 What's Included

- `Virtual Play Server.exe` → Your actual virtual controller server.
- `ViGEmBusSetup.exe` → Required driver to emulate Xbox 360 controllers.

---

## 🚀 Installation Instructions

### 🔹 Step 1: Install ViGEm

> ViGEm is a driver that lets the server emulate an Xbox 360 controller on your PC.

1. Run the included `ViGEmBusSetup.exe`.
2. Follow the on-screen instructions to install the driver.
3. After successful installation, restart your PC (recommended).

🛠 If you're downloading manually:  
You can also get it from the official source:  
👉 https://vigem.org/projects/ViGEm/ViGEm-Bus-Driver/

---

### 🔹 Step 2: Run the Remote Play Server

1. Run `Virtual Play Server.exe` (included in this folder or installed via setup).
2. The server window will launch and show your:
   - **Local IP Address**
   - **Connected Devices**
   - **Controller Slot Status (Player 1, 2, 3...)**
3. Make sure this window stays open while playing.

---

## 📱 Connect Your Android Phone

1. Install the **Virtual Play ** app on your Android phone.
2. Ensure your phone and PC are connected to the **same network**.
3. Open the app → Select your PC from the device list → Tap to connect.
4. Start controlling your PC games instantly!

---

## 🛠 Troubleshooting

### ❌ Controller Not Detected in Game?
- Ensure **ViGEmBus** is installed and running (check Device Manager → System Devices → ViGEmBus).
- Try restarting the server and game.
- Make sure the game supports **Xbox 360 controllers**.

### 📶 Phone not finding the server?
- Ensure both devices are on the **same network**.
- Disable VPN or firewall that might block discovery.
- Restart your Wi-Fi or switch networks temporarily.

---
