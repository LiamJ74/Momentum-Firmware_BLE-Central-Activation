# Custom Firmware for Flipper Zero

This is a custom firmware for the Flipper Zero device. It is a fork designed to provide enhanced features and customization options.

## Features

- **Feature-rich**: Includes many third-party apps and features.
- **Stable**: Focused on providing a stable user experience.
- **Customizable**: Extensive customization options for UI and behavior.

## Installation

### Build it yourself

To download the repository:
```bash
$ git clone --recursive <your-repo-url>
$ cd <repo-dir>/
```

To flash directly to the Flipper (Needs to be connected via USB, qFlipper closed)
```bash
$ ./fbt flash_usb_full
```

To compile a TGZ package
```bash
$ ./fbt updater_package
```

## Credits

Based on the work of the Flipper Devices team and various community contributors.
