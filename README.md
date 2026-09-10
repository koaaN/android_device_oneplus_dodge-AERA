# AERA Recovery Project device tree for OnePlus 13 (dodge)

Device configuration and recovery ramdisk assets used to build AERA Recovery
Project for the OnePlus 13 (`dodge`).

## Working

- Display and touch, including fastbootd
- Data decryption
- Flashing, backup, and restore
- MTP and USB OTG storage
- ADB and fastbootd
- Wi-Fi and network storage support
- GPU-accelerated recovery UI
- Audio and haptics
- Factory reset

## Build

Place this repository at `device/oneplus/dodge` in the AERA 16.0 source tree,
then build with:

```sh
source build/envsetup.sh
lunch twrp_dodge-bp2a-eng
mka adbd recoveryimage
```

## History

This repository retains the commit history of
[`android_device_oneplus_dodge-orangefox`](https://github.com/koaaN/android_device_oneplus_dodge-orangefox)
and continues development for AERA Recovery Project on the `aera-16.0` branch.
