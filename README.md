zzInoVIDPID
==========
VID/PID definitions for all common USB to serial chips for the [Arduino](https://arduino.cc) IDE. Used to identify ports listed on the **Tools > Port** menu.

Arduino boards that are based on ATmega32U4 or use the ATmega16U2/8U2 chips for the USB to serial interface display the board name in the **Tools > Port** menu. Other commonly used boards have different USB to serial chips without customized VID/PID, and thus do not show the board name in the menu. If you have multiple serial ports on your computer, it can get very confusing to remember which port is which. This project helps to reduce this confusion by labeling the ports of common USB to serial chips in the Arduino IDE **Tools > Port** menu with the chip name.


## Installation
There are two options for installing **zzInoVIDPID** in the Arduino IDE:
#### Boards Manager Installation(requires Arduino IDE version 1.6.4 or greater)
- Open the Arduino IDE.
- Open the **File > Preferences** menu item.
- Enter the following URL in **Additional Boards Manager URLs**: https://per1234.github.io/zzInoVIDPID/package_per1234_zzInoVIDPID_index.json
- Open the **Tools > Board > Boards Manager...** menu item.
- Wait for the platform indexes to finish downloading.
- Scroll down until you see the **zzInoVIDPID** entry and click on it.
  - **Note**: If you are using Arduino IDE 1.6.6 you may need to close **Boards Manager** and then reopen it before the **zzInoVIDPID** entry will appear.
- Click **Install**.
- After installation is complete close the **Boards Manager** window.
- **File > Quit**
- Restart the Arduino IDE.

#### Manual Installation
- Download the zzInoVIDPID files here: https://github.com/per1234/zzInoVIDPID/archive/master.zip
- Extract the .zip file.
- Move the extracted folder into the **hardware** folder in your sketchbook folder. You can find the location of your sketchbook folder at **File > Preferences > Sketchbook location:**.
- If the Arduino IDE is running then restart it.


## Defined parts
- FTDI
  - FT232x
  - FT245x
  - FT230x
  - FT231x
  - FT234XD
  - FT2232x
  - FT4232H
- Bricked counterfeit FTDI FT232
- WCH CH340/CH341
- Silicon Labs CP210x
- Prolific PL2303
- Microchip MCP2221
- Cypress CY7C65213
- Holtek HT42B534
- If you would like me to add a part please [open an issue](https://github.com/per1234/zzInoVIDPID/issues/new) or a [pull request](https://github.com/per1234/zzInoVIDPID/compare).


## Contributing
Pull requests or issue reports are welcome! Please see the [contribution rules](https://github.com/per1234/zzInoVIDPID/blob/master/.github/CONTRIBUTING.md) for instructions.


## Ports menu before:
![before screenshot](https://github.com/per1234/zzInoVIDPID/raw/screenshots/before.png)


## Ports menu after:
![after screenshot](https://github.com/per1234/zzInoVIDPID/raw/screenshots/after.png)
