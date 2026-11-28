<div align="center">

# BlackBerry Passport — Retail OS 10.3.3.3216 Autoloaders
### Initial Setup & Offline BlackBerry ID Bypass (`SQW100-1` / `SQW100-4`) — Standard & Hybrid Root/VoLTE Editions

![Device](https://img.shields.io/badge/Device-BlackBerry%20Passport%20%2F%20Silver%20Edition-000000?style=for-the-badge&logo=blackberry)
![OS](https://img.shields.io/badge/OS-Retail%2010.3.3.3216-0078D7?style=for-the-badge)
![Status](https://img.shields.io/badge/Tested%20On-Passport%20Silver%20Edition%20(Working)-2ea44f?style=for-the-badge)
![Root](https://img.shields.io/badge/Hybrid%20Build-AutoRoot%20v4%20%2B%20SSH%20%2B%20VoLTE-8a2be2?style=for-the-badge)
![Author](https://img.shields.io/badge/By-IkerXD1437-ff6600?style=for-the-badge)

</div>

---

> [!IMPORTANT]
> Unlike leaked **Developer OS** autoloaders floating around online, both editions in this repository are patched directly from the **official commercial/retail BlackBerry OS 10.3.3.3216** image. **Tested and verified working properly on a BlackBerry Passport Silver Edition (`SQW100-4`)**: there are **no debug/CPU overlays**, no developer GUIs, and all native features (including **FM Radio**, **Mobile Data**, **Wi-Fi**, **Bluetooth**, and **Android Runtime**) remain 100% intact.

## Downloads (Releases)

All files are hosted directly in the **[Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases)** section of this repository. Choose the edition that matches your needs:

| Edition | Package | Location | Notes |
| :--- | :--- | :--- | :--- |
| **Standard Edition** *(Clean Stock + Bypass)* | **`BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip`** (`1.88 GB`) | **[GitHub Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases/tag/v1.0.0)** | Clean Retail `10.3.3.3216` Autoloader (unrooted) + 10-language offline `README` |
| **Hybrid Root + VoLTE Edition** *(Power User)* | **`BB_Passport_10.3.3.3216_Retail_SetupBypass_Root_VoLTE_by_IkerXD1437.zip`** | **[GitHub Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases/tag/v2.0.0)** | Retail `10.3.3.3216` SetupBypass + **AutoRoot v4 (`u_root`/`su`)** + **OpenSSH** + `Term49.bar` + `volte.zip` + 10-language `README.txt` |

### Required Windows USB Drivers (BlackBerry Link)
To allow Windows to detect your BlackBerry Passport during flashing, you must have the official BlackBerry USB drivers installed beforehand:
- **BlackBerry Link `1.2.3.56` (Windows Installer + USB Drivers):** Install it on your Windows PC prior to running the autoloader *(also available in **[GitHub Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases)** if uploaded)*.

### File Verification (SHA-256)

#### Standard Edition (Clean Unrooted Build)
- **Archive:** `BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip` *(includes 10-language README)*
- **Executable:** `Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.exe`

    944C04FE7F3112081BE368D0A3C523170A3621B1F6D784EDA9F6502A760221DB

#### Hybrid Root + VoLTE Edition (SetupBypass + AutoRoot v4 + OpenSSH + VoLTE)
- **Archive:** `BB_Passport_10.3.3.3216_Retail_SetupBypass_Root_VoLTE_by_IkerXD1437.zip` *(includes `Term49.bar`, `volte.zip` & 10-language `README.txt`)*
- **Executable:** `Passport_10.3.3.3216_SetupBypass_Root_VoLTE_By_IkerXD1437.exe`

    <PEGA_AQUI_EL_SHA256_DEL_NUEVO_EXE>

---

## Hardware Proof — Tested on BlackBerry Passport Silver Edition (`SQW100-4`)

Flashed and verified directly on physical hardware: clean commercial home screen without developer overlays, OS `10.3.3.3216` running smoothly, and native **FM Radio** fully operational.

| | |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/21105284-333b-4700-8b23-c72e12543594" width="280"> | <img src="https://github.com/user-attachments/assets/b972e270-3083-4335-967a-80bb65be3193" width="280"> |
| <img src="https://github.com/user-attachments/assets/0e58994f-eaca-4b22-a90b-167851f6fb0d" width="280"> | <img src="https://github.com/user-attachments/assets/f67d818d-1ec4-4c0b-a253-a65b90399766" width="280"> |

---

## Technical Summary & Edition Comparison

| Parameter | Standard Edition | Hybrid Root + VoLTE Edition |
| :--- | :--- | :--- |
| **Supported Models** | BlackBerry Passport (`SQW100-1`) & Silver Edition (`SQW100-4`) | BlackBerry Passport (`SQW100-1`) & Silver Edition (`SQW100-4`) |
| **Hardware Tested** | BlackBerry Passport Silver Edition (`SQW100-4`) | BlackBerry Passport Silver Edition (`SQW100-4`) |
| **OS Version** | Retail BlackBerry OS `10.3.3.3216` (Commercial Build) | Retail BlackBerry OS `10.3.3.3216` (Commercial Build) |
| **Bypass Scope** | Initial Setup Wizard & Offline BlackBerry ID (`BBID`) | Initial Setup Wizard & Offline BlackBerry ID (`BBID`) — unblocks USB/Sachesi/DBBT |
| **Root Access** | Stock security (unrooted) | **AutoRoot v4 integrated (`u_root` / `su` root shell)** |
| **Remote SSH** | Not included | **OpenSSH daemon (`sshd`) enabled on boot (root access)** |
| **VoLTE / IMS Support** | Not included | **`Term49.bar` & `volte.zip` (`ims_manager` / VoLTE Manager) included** |
| **Native Features** | FM Radio, Mobile Data, Wi-Fi, Bluetooth & Android Runtime intact | FM Radio, Mobile Data, Wi-Fi, Bluetooth & Android Runtime intact |

---

## Flashing Instructions — Standard Edition

1. Install **BlackBerry Link `1.2.3.56`** on your Windows PC so the official BlackBerry USB drivers are registered.
2. Download and extract **`BB_Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.zip`** from **[GitHub Releases](https://github.com/IkerXD1437/BlackBerry-Passport-10.3.3.3216-Retail-SetupBypass/releases)**.
3. Power off your BlackBerry Passport completely.
4. Run **`Passport_10.3.3.3216_Retail_SetupBypass_by_IkerXD1437.exe`** as Administrator on Windows (`Connecting to Bootrom...` will appear).
5. Connect the powered-off BlackBerry Passport via USB cable. The LED will flash green/blue and the autoloader will wipe and flash the retail OS automatically.
6. Wait until the command window closes and the device reboots into the home screen (first boot takes several minutes).

---

## Hybrid Root + VoLTE Edition (`SetupBypass + AutoRoot v4 + OpenSSH + VoLTE`)

### Why a Hybrid Build?
Standard AutoRoot v4 images built on untouched commercial OS `10.3.3.3216` get stuck on the mandatory BlackBerry ID / Initial Setup Wizard when BlackBerry's legacy activation servers are unreachable, blocking USB development connections (`Sachesi` / `Darcy's BB Tools`) and preventing `firstlaunch` root initialization from completing.

By merging the **Retail `10.3.3.3216` SetupBypass** with **AutoRoot v4**, this hybrid build boots directly to the commercial home screen, completes `firstlaunch` root provisioning automatically upon connecting to Wi-Fi, and unlocks full USB sideloading, SSH access, and VoLTE/IMS module installation out of the box.

### What's Inside the Hybrid Package
1. **`Passport_10.3.3.3216_SetupBypass_Root_VoLTE_By_IkerXD1437.exe`** — Full Retail OS `10.3.3.3216` + Radio autoloader with SetupBypass and AutoRoot v4 pre-injected into the QNX6 system image (`@IFS.4.ufs`).
2. **`Term49.bar`** — Native BlackBerry 10 terminal emulator required to execute local root commands on-device.
3. **`volte.zip`** — Qualcomm `qc8974` IMS / VoLTE addon package (`devnp-volte-swcrypto.so`, `ims_manager`, and **VoLTE Manager** app).
4. **`README.txt`** — Complete 10-language offline installation & troubleshooting guide.

### Flashing & Post-Flash Setup — Hybrid Edition

1. **Flash the Hybrid Autoloader:**
   - Install **BlackBerry Link `1.2.3.56`** on your Windows PC.
   - Extract **`BB_Passport_10.3.3.3216_Retail_SetupBypass_Root_VoLTE_by_IkerXD1437.zip`**.
   - Power off your BlackBerry Passport completely, run **`Passport_10.3.3.3216_SetupBypass_Root_VoLTE_By_IkerXD1437.exe`** as Administrator, and connect the phone via USB cable.
   - Wait until the autoloader finishes and the Passport boots straight into the home screen.

2. **Initialize AutoRoot v4:**
   - Connect the BlackBerry Passport to a **Wi-Fi** network.
   - Wait ~15–20 seconds until the BlackBerry Hub notification appears confirming that **AutoRoot v4** has successfully rooted the device.

3. **Install `Term49.bar` via USB:**
   - On the Passport, go to **Settings → Security and Privacy → Development Mode**, toggle it **ON**, and set a temporary password (e.g. `0184`).
   - Connect the phone to your Windows PC via USB and install **`Term49.bar`** using **Darcy's BB Tools** (`169.254.0.1`) or **Sachesi**.

4. **Transfer & Install `volte.zip` (VoLTE / IMS Module):**
   - Copy **`volte.zip`** (keep it zipped) into the device's **Downloads** folder (`/accounts/1000/shared/downloads/volte.zip`) via USB storage or local HTTP transfer.
   - Ensure **Wi-Fi** is connected (required by `ims_manager` to fetch carrier profiles), open **Term49** on the Passport, grant all requested permissions, and execute:

         u_root
         /var/rootdata/installer /accounts/1000/shared/downloads/volte.zip

   - Wait until the console displays `Installation completed successfully` (and `[BBE] WAITING_FOR_LTE` in `/var/log/installer.log`), then **reboot** the device.

5. **Configure Carrier APN & Verify VoLTE:**
   - Go to **Settings → Network and Connections → Mobile Network**:
     - Set **Network Mode** to `4G & 3G & 2G`.
     - Enable **Data Services** (and **Data Services While Roaming** if you use an MVNO).
     - Open **APN**, enter your carrier's IPv4 APN (for example, `internet.digimobil.es` on DIGI Spain or `telefonica.es` on Movistar), and save.
   - Open **VoLTE Manager** on the home screen and make a test call with Wi-Fi turned off to verify whether your SIM/carrier maintains **4G / LTE** during voice calls.
   - *(Note: VoLTE availability depends on carrier MBN modem profile compatibility for Snapdragon 801 `qc8974` and carrier-side IMS/IMEI provisioning. Major carriers with native Qualcomm MBN profiles such as Movistar/Telefónica have higher out-of-the-box compatibility than newer MVNOs).*

6. **Post-Setup Security Hardening (Recommended):**
   - Turn off **Development Mode** in **Settings → Security and Privacy → Development Mode**.
   - If you no longer need remote SSH access over Wi-Fi while keeping local `u_root` and VoLTE active, run inside **Term49**:

         u_root
         rm -f /var/rootdata/use.sshd && reboot

---

<div align="center">
<sub>Compiled, documented, and hardware-tested on a <b>BlackBerry Passport Silver Edition (SQW100-4)</b> by <b>IkerXD1437</b></sub>
</div>
