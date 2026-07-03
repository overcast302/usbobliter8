# usbobliter8

Erasing tool for A12/A13 iOS devices. Uploads a patched iBEC, and triggers iOS' built-in obliteration (erase all).

## Usage

1. Enter PWND DFU mode with [usbliter8](https://github.com/prdgmshift/usbliter8)
2. Run `usbobliter8` and click `Obliter8!`
3. Device reboots and begins erasing

## Requirements

- macOS 10.13+, Windows, or Linux
- libusb:
  - **macOS**: `brew install libusb`
  - **Linux**: `apt install libusb-1.0-0-dev`
  - **Windows**: Install [Zadig](https://zadig.akeo.ie/) and replace the Apple DFU driver with `libusbK`