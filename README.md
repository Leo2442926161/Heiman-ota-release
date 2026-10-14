# Heiman OTA Release

This repository hosts firmware files that cannot be delivered through the official OTA channels.

## Purpose

Some firmware versions may not be eligible for release via the official OTA update process for various reasons. To ensure users still have access to these versions, we publish them here as standalone files.

## Important Notes

- Firmware provided in this repository is **not** distributed through official OTA.
- It may not have completed the full official release and validation process.
- Flashing firmware carries risks. Proceed at your own discretion and back up your data first.
- Use the correct firmware file that matches your exact device model and hardware version.

## Firmware Files

| Device | Model | Version | File |
| ------ | ----- | ------- | ---- |
| Smoke Alarm | HS1SA-E | EF2 V15 | `zigbee/smoke_alarm/HS1SA-E/HS1SA_EF2_V15_20260407.ota` |

## How to Use

1. Identify your device model and current firmware version.
2. Download the matching `.ota` file from the table above.
3. Flash the firmware using a compatible OTA tool or your hub's local OTA interface.
4. Verify the version after the update is complete.
