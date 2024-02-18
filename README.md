# Password Entry System

This Arduino script implements a password entry system using a keypad and an LCD display. It prompts the user to enter a password, compares it with the preset master password, and activates a signal pin if the passwords match.

## Instructions

### Libraries Required
- Keypad.zip: This library provides functions for interacting with the keypad.
- liquidcrystal_i2c.zip: This library enables communication with the LCD display via I2C.

Ensure that these libraries are installed in the `Documents\Arduino\libraries\` directory.

### Keypad Configuration
Depending on your keypad type, use either the `keypad_3x4.ino` or `keypad_4x4.ino` project files.

## Installation

1. Download the necessary libraries and unzip them.
2. Move the extracted library folders (`Keypad` and `LiquidCrystal_I2C`) to your Arduino libraries folder (typically located at `Documents\Arduino\libraries\`).
3. Connect your Arduino board and upload the appropriate script (`keypad_3x4.ino` or `keypad_4x4.ino`) to the board using the Arduino IDE.
4. Test the system by entering the preset master password. If entered correctly, the signal pin will activate.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
