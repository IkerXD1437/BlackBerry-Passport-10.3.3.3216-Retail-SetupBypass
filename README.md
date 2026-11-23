<div align="center">

# BlackBerry Passport — Retail OS 10.3.3.3216 Autoloader
### Initial Setup & Offline BlackBerry ID Bypass (`SQW100-1` / `SQW100-4`)

![Device](https://img.shields.io/badge/Device-BlackBerry%20Passport%20%2F%20Silver%20Edition-000000?style=for-the-badge&logo=blackberry)
![OS](https://img.shields.io/badge/OS-Retail%2010.3.3.3216-0078D7?style=for-the-badge)
![Status](https://img.shields.io/badge/Tested%20On-Passport%20Silver%20Edition%20(Working)-2ea44f?style=for-the-badge)
![Author](https://img.shields.io/badge/By-IkerXD1437-ff6600?style=for-the-badge)

</div>

---

> [!IMPORTANT]
> Unlike leaked **Developer OS** autoloaders floating around online, this build is patched directly from the **official commercial/retail BlackBerry OS 10.3.3.3216** image. **Tested and verified working properly on a BlackBerry Passport Silver Edition (`SQW100-4`)**: there are **no debug/CPU overlays**, no developer GUIs, and all native features (including **FM Radio** and **Mobile Data**) remain 100% intact.

## Downloads (Releases)

All files are hosted directly in the **[Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases/latest)** section of this repository:

| Package | Location | Notes |
| :--- | :--- | :--- |
| **`BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip`** (`1.88 GB`) | **[GitHub Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases/latest)** | Retail `10.3.3.3216` Autoloader + 10-language offline `README` |

### Required Windows USB Drivers (BlackBerry Link)
To allow Windows to detect your BlackBerry Passport during flashing, you must have the official BlackBerry USB drivers installed beforehand:
- **BlackBerry Link `1.2.3.56` (Windows Installer + USB Drivers):** Install it on your Windows PC prior to running the autoloader *(also available in **[GitHub Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases/latest)** if uploaded)*.

### File Verification (SHA-256)
- **Archive:** `BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip` *(includes 10-language README)*
- **Executable:** `Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.exe`
```text
944C04FE7F3112081BE368D0A3C523170A3621B1F6D784EDA9F6502A760221DB
```

---

## Hardware Proof — Tested on BlackBerry Passport Silver Edition (`SQW100-4`)

Flashed and verified directly on physical hardware: clean commercial home screen without developer overlays, OS `10.3.3.3216` running smoothly, and native **FM Radio** fully operational.

| | |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/21105284-633b-4700-8b23-c72e12543594" width="280"> | <img src="https://github.com/user-attachments/assets/b972e270-3083-4335-967a-80bb65be3193" width="280"> |
| <img src="https://github.com/user-attachments/assets/0e58994f-eaca-4b22-a90b-167851f6fb0d" width="280"> | <img src="https://github.com/user-attachments/assets/f67d818d-1ec4-4c0b-a253-a65b90399766" width="280"> |

---

## Technical Summary

| Parameter | Detail |
| :--- | :--- |
| **Supported Models** | BlackBerry Passport (`SQW100-1`) & Silver Edition (`SQW100-4`) |
| **Hardware Tested** | BlackBerry Passport Silver Edition (`SQW100-4`) |
| **OS Version** | Retail BlackBerry OS `10.3.3.3216` (Commercial Build) |
| **Bypass Scope** | Initial Setup Wizard & Offline BlackBerry ID (`BBID`) |
| **Native Features** | FM Radio, Mobile Data, Wi-Fi, Bluetooth & Android Runtime intact |

---

## Flashing Instructions

1. Install **BlackBerry Link `1.2.3.56`** on your Windows PC so the official BlackBerry USB drivers are registered.
2. Download and extract **`BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip`** from **[GitHub Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases/latest)**.
3. Power off your BlackBerry Passport completely.
4. Run **`Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.exe`** as Administrator on Windows (`Connecting to Bootrom...` will appear).
5. Connect the powered-off BlackBerry Passport via USB cable. The LED will flash green/blue and the autoloader will wipe and flash the retail OS automatically.
6. Wait until the command window closes and the device reboots into the home screen (first boot takes several minutes).

---

<div align="center">
<sub>Compiled, documented, and hardware-tested on a <b>BlackBerry Passport Silver Edition (SQW100-4)</b> by <b>IkerXD1437</b></sub>
</div>
