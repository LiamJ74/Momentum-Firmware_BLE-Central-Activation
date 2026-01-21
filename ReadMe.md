# Custom Firmware for Flipper Zero

This is a custom firmware for the Flipper Zero device, designed to push the boundaries of what's possible while maintaining stability and ease of use.

## Features

*   **Enhanced Customization**: Change animations, icons, main menu layout, and more with the Asset Packs system.
*   **Advanced Tools**: Includes powerful applications like Bad-Keyboard, BLE Spam, and enhanced Sub-GHz capabilities.
*   **Improved UI**: Redesigned interface elements for a smoother user experience.
*   **Extended Functionality**: Broader protocol support and additional JavaScript API features.

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

This firmware is a fork of **Momentum Firmware**. We gratefully acknowledge the Momentum team for their extensive work, innovation, and contributions to the Flipper Zero community.

Also based on the work of the Flipper Devices team (Official Firmware) and the Unleashed Firmware team.
