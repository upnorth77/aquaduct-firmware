# Release notes

## 0.21.7 - Beta

- Shows Wi-Fi connection progress and the last ESP32 disconnect reason and
  numeric code in the joining page and Diagnostics.
- Includes the target network and full station MAC address for matching
  access-point records; distinguishes IP-address timeout and browser contact loss.
- Corrects the joining page's character encoding and opening message.
- Includes matching Quick Start and User Manual PDFs.
- Firmware build, documentation checks, and mocked browser tests passed.
  Physical Wi-Fi behavior remains untested; this improves reporting and does
  not establish a fix for connection failures.
- Retains Rev A prototype and one-source-only power requirements.

## 0.21.6 - Beta

- Moves Weekly plan near the top of Edit schedules, below profile controls
  and above schedule import. Weekly scheduling behavior is unchanged.
- Includes matching Quick Start and User Manual PDFs.
- Retains Rev A prototype and one-source-only power requirements.

## 0.21.5 - Beta

- Uses a clearer SVG gear for Settings.
- Combines schedule navigation under Schedules, with Edit schedules and
  Create new schedule tabs replacing Advanced editor and Wizard labels.
- Imports saved schedules from another Aquaduct from the receiving controller.
  Choose a source controller, source schedule, and unique local name.
- Imported schedules stay inactive; source operation and receiving-controller
  master intensity, weekly plan, current output, and safety settings are preserved.
- Both controllers need firmware supporting pull imports. Existing profiles are
  never overwritten. Review and save an imported profile before using it.
- Includes matching Quick Start and User Manual PDFs.
- Build and mocked desktop/mobile UI checks passed. Physical two-controller
  transfer has not been validated. Retains Rev A prototype and one-source-only
  power requirements.

## 0.21.3 - Beta

- Adds configurable 12-hour, 24-hour, or automatic time display.
- Improves Guided setup and Advanced editor schedule navigation and preview.
- Enables the selected schedule whenever its changes are saved.
- Adds blue Wi-Fi setup, amber Wi-Fi-loss, red fault, and 60-second green
  healthy-startup status indications.
- Adds a GitHub link to the controller's Firmware Update page.
- Includes updated Quick Start and User Manual PDFs.

## 0.21.2 — Beta

- Current beta firmware for Aquaduct Rev A prototype controllers.
- Includes the matching Quick Start Guide and User Manual.
- Supports local web configuration, schedules, controller grouping, MQTT,
  diagnostics, backups, and local firmware updates.
- Retains the Rev A one-power-source-only safety requirement.

