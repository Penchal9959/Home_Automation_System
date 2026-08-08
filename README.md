# Home Automation System

A reviewed and corrected version of this project, with a build check and
fuller documentation, is in [embedded-iot-projects / home-automation](https://github.com/Penchal9959/embedded-iot-projects/tree/main/home-automation) alongside the others from the same
series.

## What this was

Four mains appliances switched from a phone over Bluetooth. The Android app
sends a single character per command; the sketch maps each to a relay.
Voice control is the phone's own speech-to-text feeding the same channel, not
anything running on the microcontroller.

## Hardware

Arduino UNO, HC-05 Bluetooth module, four-channel relay board.

## Licence

[MIT](LICENSE)
