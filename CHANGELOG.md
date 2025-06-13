# Changelog

All notable changes to this project are documented in this file.

## [2024-11-19]
- Add `supportedFanSpeeds` to the configure method for Google Home support. Run **Configure** after updating.

## [2021-11-30]
- Added push and hold methods for Hubitat capability updates.

## [2021-11-02]
- Updated handling of `componentSetColorTemperature` to match Hubitat changes.

## [2021-05-26]
- Update method used to determine secure or non-secure communication.

## [2021-03-10]
- Added parameter numbers to preference descriptions.

## [2020-10-01]
- Added custom command `setConfigParameter(number, value, size)`.

## [2020-09-01]
- Added child devices for LED color and intensity.

## [2020-08-27]
- Cleaned up device fingerprint info.

## [2020-08-26]
- Fixed deletion of Hubitat child devices.

## [2020-08-25]
- Fixed button events not being sent correctly on C7 hub.

## [2020-08-14]
- Added configuration parameter 51 for firmware 1.36+.

## [2020-08-13]
- Fixed SupervisionGet error.

## [2020-08-05]
- Added S2 support for C-7 hub.

## [2020-08-04]
- Added `cycleSpeed()` command for fan child device.

## [2020-08-03]
- Added `reset()` command to clear energy accumulation numbers.

## [2020-07-10]
- Fan child device now shows `speed` correctly when controlled from the switch.

## [2020-06-29]
- Switched to using "Hampton Bay Fan Component" child device.

## [2020-06-28]
- Fixed power and energy report parsing and local protection setting.
