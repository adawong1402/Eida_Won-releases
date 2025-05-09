# Eida Releases

This repository hosts stable builds of custom Android ROMs for the ***Xiaomi Redmi Note 10 Pro/Pro Max (sweet)***.

## 📁 Releases

You can find the latest builds under the [Releases](../../releases) section. Each release may include:
- ROM ZIP

> **Note**: Make sure to download the correct file for your device.

---

## 🔁 Flashing Guide

### 🧹 Clean Flash (Recommended for major updates or switching ROMs)

1. **Backup your data** (apps, internal storage, etc.)
2. Boot into **custom recovery** (e.g., TWRP/OrangeFox or Lineage Recovery)
3. **Wipe** the following:
   - `Dalvik / ART Cache`
   - `Cache`
   - `Data`
4. Flash the ROM:
   - `Install > Select the downloaded ROM ZIP > Swipe to flash`
5. (Optional) Flash additional packages:
   - GApps (if not included in ROM)
   - Custom Kernel (Magisk/KSU/KSUN/APatch)
   - This [Recovery-EROFS](https://github.com/basamaryan/android_device_xiaomi_sweet-TWRP/releases/download/R11.1_7/OrangeFox-R11.1_7-Unofficial-sweet-EROFSCompression.zip).
6. Reboot to recovery.
7. Format/Wipe Data.
8. Reboot to system.

---

### 🧼 Dirty Flash (Only if staying on the same ROM)

1. Boot into **custom recovery**
2. **Wipe**:
   - `Dalvik / ART Cache`
   - `Cache`
3. Flash the ROM:
   - `Install > Select the new ROM ZIP > Swipe to flash`
4. (Optional) Flash any other updates like **Custom kernel** (Magisk/KSU/KSUN/APatch)
5. Reboot system.

> ⚠️ **Note**: Dirty flashing between major Android versions or different ROM bases is discouraged and may cause issues.

---

## 🔒 Disclaimer

This software is provided "as is", without warranty of any kind. Flashing custom ROMs can void your warranty and carries a risk of bricking your device. Proceed at your own risk.
