# ⚡ Power Setting Manager

[![Version](https://img.shields.io/badge/version-1.8.2-blue.svg)](https://github.com/your-username/power-setting-manager/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D4.svg)](https://microsoft.com/windows)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

**Power Setting Manager** is a feature-rich Windows application built to give you total, automated control over your system's power plans, timeouts, physical button actions, and sleep states through a clean, modern interface.

---

## 📌 Features Overview

* **📊 Complete Power Dashboard**: View and configure idle timeouts for Display, System Sleep, Hibernation, and Mechanical Hard Disks for both **Plugged In (AC)** and **On Battery** modes.
* **🌙 Never Mode & Auto-Restore**: Prevents your system from going to sleep or turning off screens with a single toggle. Includes a safety restore function to reset original timeouts on restart.
* **🔘 Physical Buttons & Lid Actions**: Custom hardware responses (Closing lid, Power button, Sleep button) mapped independently for AC and Battery states, syncable across all Windows power plans.
* **⚡ Automated Power Plan Auto-Switching**: Automatically switches Windows power plans (e.g., *High Performance* on AC, *Battery Saver* on Battery) using scheduled task automation.
* **⏱️ Presets & Backups**: Instantly save, edit, duplicate, or apply predefined timeout profiles (*Recommended*, *Windows 11 Default*, or custom user profiles).
* **💤 Advanced Sleep Controls**: Global toggles for Windows Hibernation (`hiberfil.sys`) and Hybrid Sleep configurations.

---

## 📸 Interface & Navigation

### 1. Dashboard
The core interface to quickly modify idle timeouts and toggle Never Mode.
* **AC / Battery Split Controls**: Fine-tune display and sleep timeouts independently.
* **Never Mode**: One-click override to keep your PC awake during downloads, rendering, or long operations.

### 2. Buttons & Lid Manager
Control how physical device triggers behave.
* Set custom responses for:
  * Notebook Lid Closure
  * Chassis Power Button
  * Dedicated Keyboard Sleep Key
* Manage System-Level Features:
  * Enable/Disable Windows Hibernation.
  * Enable/Disable Hybrid Sleep on AC and Battery.

### 3. Presets & Backups
Quickly switch entire timeout configurations without creating new full power plans.
* Apply predefined profiles in one click.
* Save current timeout rules as custom reusable presets.

### 4. Power Plans
Manage all installed Windows power schemes.
* Auto-switch profiles based on charger status (Plugged in vs. On Battery).
* Edit times, duplicate, or activate built-in plans (*High Performance*, *Balanced*, *Battery Saver*, *Recommend Plan*).

---

## 📥 Installation

### Quick Install (Executable Setup)
1. Go to the [Releases Page](https://github.com/your-username/power-setting-manager/releases).
2. Download **`PowerSettingManager-1.8.2-Setup.exe`**.
3. Run the installer and complete the setup wizard.

---

## 🚀 How to Use

1. **Change Timeouts**: Navigate to **Dashboard**, select your desired delay for AC or Battery, and click **Save Timeouts**.
2. **Setup Auto-Switching**:
   * Open the **Power Plans** tab.
   * Turn on **Auto-switch by power source**.
   * Select your preferred AC plan (e.g., *High Performance*) and Battery plan (e.g., *Battery Saver*).
   * Click **Save Auto-Switch**.
3. **Configure Lid/Power Button**:
   * Open **Buttons & Lid Manager**.
   * Select the preferred actions from the dropdown menus for AC and Battery modes.
   * Enable **Apply to all power plans** to ensure consistency across mode switches.
   * Click **Save Actions**.

---

## 🛠️ Built With

* **UI/UX Framework**: Modern dark-themed GUI interface.
* **System APIs**: Windows Power Management APIs (`PowerCfg`).
* **OS Support**: Windows 10 and Windows 11 (x64).

---

## 🤝 Contributing

Contributions, feature requests, and bug reports are welcome!
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AwesomeFeature`)
3. Commit your Changes (`git commit -m 'Add some AwesomeFeature'`)
4. Push to the Branch (`git push origin feature/AwesomeFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
