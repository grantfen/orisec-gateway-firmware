# Orisec Gateway Firmware

One-click web installer for the Orisec Gateway firmware (Waveshare ESP32-P4-NANO).

## Install

Open **https://grantfen.github.io/orisec-gateway-firmware/** in desktop **Chrome** or **Edge**,
plug the board in by USB, and click **Connect & Install**.

## Manual install (any OS)

```
pip install esptool
esptool --chip esp32p4 -p <PORT> write-flash 0x0 firmware/orisec-gateway-1.0.6.bin
```

Replace `<PORT>` with your serial port (e.g. `COM4` on Windows, `/dev/ttyUSB0` on Linux).

---

This repository contains only the **compiled firmware** and the installer page.
It does not contain source code.
