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

## Download Mirrors

| Mirror | Host | Direct Link | Notes |
| :--- | :--- | :--- | :--- |
| **Mirror 1** | Internet Archive | **[Download from Archive.org](https://archive.org/details/bb-passport-10.3.3.3216-retail-setup-bypass-by-iker-xd-1437)** | Permanent preservation mirror |
| **Mirror 2** | MediaFire | **[Download from MediaFire](https://www.mediafire.com/file/vxiylzttd0b8gpg/BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip/file)** | Fast permanent mirror |
| **Mirror 3** | Gofile | **[Download from Gofile](https://gofile.io/d/EyridQcY)** | High-speed direct mirror |

### File Verification (SHA-256)
* **Archive:** `BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip` *(includes 10-language README)*
* **Executable:** `Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.exe`
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
| **Hardware Tested** | BlackBerry Passport Silver Edition (`SQW100-4`) — Verified working |
| **Base Firmware** | Official Retail `10.3.3.3216` (OS + Radio) |
| **Modification** | Patched `autorun::1` → `autorun::0` in system `navigator/config` node |
| **Working Features** | Native FM Radio, Wi-Fi, Mobile Data, Bluetooth, BlackBerry Hub, Android Runtime |

---

## How to Flash (Windows)

1. Install **BlackBerry Link** or official **BlackBerry USB Drivers** on your Windows PC.
2. Extract `BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip`.
3. **Power off** your BlackBerry Passport completely (hold the top power button until the red LED turns off).
4. Right-click `Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.exe` → **Run as administrator**.
5. Connect the phone directly to a motherboard USB port. The LED will turn **solid green** while flashing.
6. Once it reaches `100%`, the console will close and the phone will reboot straight to the home screen *(first boot takes 2–4 minutes)*.

---

<div align="center">
<sub>Built, patched, and hardware-tested on a BlackBerry Passport Silver Edition by <b>IkerXD1437</b></sub>
</div>
