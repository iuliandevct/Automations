# Home Automation

Small local home automation project for ESP32-CAM devices and Home Assistant.

## Device

Current device:

- ESP32-CAM AI Thinker
- Static IP: `192.168.1.160`
- Wi-Fi SSID: `PANANET`
- Camera endpoint: `http://192.168.1.160/capture`
- Relay endpoints:
  - `http://192.168.1.160/relay/on`
  - `http://192.168.1.160/relay/off`
  - `http://192.168.1.160/status`

## Arduino IDE Settings

Install ESP32 boards:

```text
File -> Preferences -> Additional Boards Manager URLs
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
```

Then:

```text
Tools -> Board -> ESP32 Arduino -> AI Thinker ESP32-CAM
Upload Speed: 115200
```

Upload wiring:

```text
USB-Serial 5V  -> ESP32-CAM 5V
USB-Serial GND -> ESP32-CAM GND
USB-Serial TX  -> ESP32-CAM U0R / RX
USB-Serial RX  -> ESP32-CAM U0T / TX
GPIO0          -> GND only while uploading
```

After upload, remove `GPIO0 -> GND` and press `RST`.

