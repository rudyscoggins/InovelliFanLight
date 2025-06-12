# Inovelli Fan + Light Driver

This repository contains a Hubitat driver for the **Inovelli LZW36 Fan/Light Switch**. It is a fork of Inovelli's official code and provides convenient control of both fan and light functions through Hubitat.

## Features
- Control fan speed and light level
- Configure LED notifications, colors and intensity
- Energy and power monitoring
- Exposes child devices for easier dashboard management
- Supports advanced configuration parameters and association groups

## Installation
1. In Hubitat, navigate to **Drivers Code** and select **New Driver**.
2. Copy the contents of `InnovelliFanLightDriver.groovy` and paste them into the driver editor.
3. Save the driver and assign it to your Inovelli LZW36 device.
4. Click **Configure** once to ensure all settings are sent to the switch.

## Usage
After installation the driver exposes commands for controlling the fan and light components individually as well as built‑in notifications. All parameters can be edited in the device preferences. See the code comments for details on each option.

## Contributing
Pull requests are welcome. Please open an issue first to discuss any major changes.

This project is released under the Apache 2.0 license.
