# NIBM Netlink Pro - Network Automation Suite

**Automated connectivity management and fault-tolerance system for NIBM students.**

![Status](https://img.shields.io/badge/Status-Stable_v4.7-success) ![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11-blue) ![Security](https://img.shields.io/badge/Security-Enterprise_Grade-shield)

## 🚀 Overview
**Netlink Pro** is a robust desktop application designed to solve frequent network timeout and connectivity interruption issues. It replaces manual captive portal logins with an automated, intelligent background agent that ensures seamless internet access for uninterrupted workflow.

## 🛠️ Tech Stack
* **Core Engine:** Python 3.12
* **Automation:** Selenium WebDriver (Headless Chrome)
* **Interface:** CustomTkinter (High-DPI Enterprise UI)
* **Backend Sync:** Google Firebase Realtime Database
* **Network API:** Windows Native WLAN API (`netsh` integration)
* **Security:** PyArmor Obfuscation & AES Encryption

## ✨ Key Features
* **Silent Operation:** Runs invisibly in the background with zero UI interruptions.
* **Smart WiFi Detection:** Automatically identifies the "NIBM" SSID and pauses operations when on other networks to save resources.
* **Fault Tolerance:** Detects packet loss (Ping spikes) or disconnections and instantly rotates credentials to a working account.
* **Enterprise Stealth:** "Quiet" UI design that hides credential details during the switching process.
* **Device Fingerprinting:** Remembers the last stable configuration for your specific machine ID.

## 🔒 Security Architecture
1.  **Client-Side Execution:** All automation runs locally on your machine. No credentials are sent to third-party servers other than the official NIBM portal.
2.  **Obfuscation:** The executable is compiled with **PyArmor**, making reverse engineering and tampering extremely difficult.
3.  **Encrypted Config:** Local configuration files are encrypted using standard cryptographic libraries.

## 📥 Installation
1.  Download the latest **`NIBM_Netlink_Pro.exe`** from the repository.
2.  Run the application.
3.  **First Run:** If the system is offline, use the "Contribute" tab to enter a single valid login to bootstrap the database connection.

## ⚠️ Disclaimer
This software is developed for **educational purposes** to demonstrate network automation and state management. It is intended to assist students in maintaining a stable connection for academic work. The developer is not responsible for misuse of this tool.

---
**Developed by Anhaj**
[GitHub](https://github.com/Anhaj0) | [LinkedIn](https://www.linkedin.com/in/anhaj-uwaisulkarni-1781a8308/)
