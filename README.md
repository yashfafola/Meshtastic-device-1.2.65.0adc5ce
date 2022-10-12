# Meshtastic-device
[![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/meshtastic/Meshtastic-device)
[![Continuous Integration](https://github.com/meshtastic/Meshtastic-device/actions/workflows/main.yml/badge.svg)](https://github.com/meshtastic/Meshtastic-device/actions/workflows/main.yml)
![GitHub all releases](https://img.shields.io/github/downloads/meshtastic/meshtastic-device/total)
---
### A few files in this repository are modified for testing and analysis purpose.

**All other source code development credit goes to respective developers and contributors.**
1. meshtastic firmware version: `1.2.65.0adc5ce`
2. Modified code files: `RangeTestPlugin.cpp` & `RangeTestPlugin.h`
3. Modifications:
    - Timestamps are now recorded in milliseconds to analyse precise latency
    - Tx payload is recorded in trasmitter device 
    - GPS time and locations are commented in rangetest plugin due to conflicting time sync between devices
    - `firmware.bin` in build directory is then explicitly used to test the devices in various scenarios
    - Modifications are made to do automatic tests for academic/scientific purpose
---

## This repository contains the device firmware used in the [Meshtastic](https://meshtastic.org) project.

Update Instructions

[For ESP32 devices click here](https://meshtastic.org/docs/getting-started/flashing-esp32)

[For nRF52 devices click here](https://meshtastic.org/docs/getting-started/flashing-nrf52)

For developer information and specific building instructions, please see the [developer doccumentation](https://meshtastic.org/docs/developers)
