# G3 MAX TUNER v2.0 — Android Studio project

## What's included
- Dark dashboard shell
- Android Bluetooth Low Energy (BLE) device scan
- Runtime permission handling for Android 8 through Android 15
- Displays discovered BLE device names, signal strength and address

## Build
1. Unzip the project.
2. Open the `G3_MAX_TUNER_v2` folder in Android Studio.
3. Allow Gradle sync to finish.
4. Connect your Android phone with USB debugging enabled, or use an emulator.
5. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).

## Test
- Turn on the scooter and keep it nearby.
- Enable Bluetooth on the phone.
- Tap "BLUETOOTH-GERÄTE SUCHEN" and grant the requested Android permissions.
- A scan lasts about 12 seconds.

## Important limitations
This is a BLE discovery prototype, not a verified MAX G3 integration. A nearby device name or address
does not prove that it is the scooter. It does not pair, read scooter telemetry, or modify firmware,
motor output, speed limits, or other vehicle settings. A verified and documented protocol is needed
before implementing read-only telemetry.
