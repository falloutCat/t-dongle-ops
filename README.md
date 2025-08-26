# t-dongle-ops
WiFi Recon &amp; Covert Display Payloads with the LILYGO T-Dongle S3

# T-Dongle Ops – Red Teaming with the LILYGO T-Dongle S3

This project documents experiments, tools, and PoCs related to the LILYGO T-Dongle S3. The goal is to use the ESP32-based board for reconnaissance, WiFi hacking, covert payloads, and AI-supported red teaming use cases.

## 🎯 Goals

- Use as a mobile recon tool (WiFi, BLE, probe requests)
- Covert payload output via the integrated display
- Tests with automated responses (AI/prompt-controlled)
- Integration with Flipper Zero or Power Delivery Over USB
- Storage & display of animated payloads (GIF, text, pattern)

## 🔧 Hardware

- LILYGO T-Dongle S3
- USB-C power bank / laptop
- (optional) WiFi capture stick, USB analyzer

## 🛠️ Tools & Libraries

- Arduino IDE or PlatformIO
- TFT_eSPI, LVGL, GFX Libs
- ESP32 WiFi Stack, Marauder, FastLED (depending on use case)
- (optional) LittleFS for local files

## 📷 Demo ideas

- WiFi probe capture + animated evaluation
- Rickroll text run or QR codes for social manipulation
- Display of AI-generated hints when target networks are “detected”

## 🧠 Status

This project is under development. Initial code will follow soon.

## 📁 Structure

```plaintext
src/          # Main code (ESP32 sketches, WiFi logic, UI)
docs/         # Ideas, sketches, documentation
tools/        # Additional helper scripts or flashing tools


