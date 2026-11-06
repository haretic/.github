# haretic
<img src="tour.gif" align="right" width="360" alt="haretic on the rabbit r1: boot, lock screen, wheel menus, Settings, installer and updates">

haretic is a custom operating system for the rabbit r1, based on Android 17 and Linux 7.3 kernel (mainline, released in October 2026).
rabbitOS is replaced entirely. Custom kernel, rootfs, drivers, vendor.
Android is based on LineageOS 24, with heavy UI modifications to fit the r1's 480x640 screen and wheel.

Install via the [haretic installer](https://github.com/haretic/installer/releases/)

Port status: beta, stable during runtime (I am daily driving it)

## What works
- WiFi/Bluetooth/BLE
- RIL/Mobile data (telephony untested)
- SoC sleep
- PowerVR GE8320 GPU acceleration and 90Hz screen refresh rate (rabbitOS cap removed)
- Camera (Hi-846) through libcamera with hardware ISP
- front and back by turning the motor
- Accelerometer and gyroscope
- Audio: speaker and microphone
- GPS
- Hardware video encode/decode (Codec2)
- Battery, fuel gauge and charging, with Lineage charging limit (down to 50%)
- USB device mode and adb; emulate USB touchpads, keyboards, flash drives, CD ROM drives or a sound card using a USB C cable
- OTA updates from the device itself

## What doesn't
- Calls and SMS untested
- Camera quality may be reduced compared to rabbitOS (WIP)
- tell me in GitHub issues
