---
layout: page
title: Installation
permalink: /install/
---

## Install ESPHome-Econet Using USB

Select your appliance type from the list below, then click the button to install ESPHome-econet on the device over USB:

{% include improvSerialButton.html %}

After the installation finishes, ESP Web Tools will automatically guide you through configuring Wi-Fi on the device using Improv over Serial (no extra software required). Please complete that step before disconnecting the device from USB. If you skipped it or the serial configuration did not succeed, you can reconnect the device and use the button above again at any time, or fall back to the Bluetooth-based method below.

## Configure ESP32 Device Wi-Fi Using Bluetooth

If you were unable to configure Wi-Fi during the USB install (for example, because Improv over Serial was skipped or your browser does not support it), you can configure Wi-Fi on an ESP32 device configured for Improv over BLE by clicking the button below while the device is powered on and in range:

{% include improvBLEButton.html %}
