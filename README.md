# CYD-Klipper
An implementation of a wireless Klipper status display on an ESP32 + 3.5" screen. Uses Moonraker to fetch data.

A simple and cheap solution to use a dedicated screen with Klipper, a 3d printing Firmware.

ESP32-3248S035C            |  3.5" display
:-------------------------:|:-------------------------:
<a href="url"><img src="images/20240121_124444.jpg" align="center" height=90% width=90% ></a>|<a href="url"><img src="images/20240121_124612.jpg" align="center" height=95% width=95%></a>
<p href="url"><img src="images/Dimensions-ESP32-3248S035.jpg" align="right" height=60% width=60% ></p>

### Required hardware

A ESP32-3248S035C is required to run this project. You can find out where to buy these on the ["ESP32 Cheap Yellow Display 3.5""](https://s.click.aliexpress.com/e/_DFOFokz) repository.

### Features
- View printer status
- View print progress
- Start a print
- Move the printer
- Manage temperature
- Extrude/Retract filament
- Execute predefined gcode macros

### Install

[There is a web-based installer available. This is only supported on Chrome, Edge or Opera, and only on Desktop.](https://operatorb.github.io/CYD-Klipper-3.5-display/)

On initial install, all data should be wiped. On updates, data should be able to be kept without issues.

There are no 'over the air' updates. Each update has to be applied manually.

### Images
3.5" display               |  Capacitive
:-------------------------:|:-------------------------:
<a href="url"><img src="images/20240121_124822.jpg" align="center" height=95% width=95% ></a>|<a href="url"><img src="images/20240121_124828.jpg" align="center" height=90% width=90% ></a>
<a href="url"><img src="images/20240121_124833.jpg" align="center" height=95% width=95% ></a>|<a href="url"><img src="images/20240121_124837.jpg" align="center" height=90% width=90% ></a>
<a href="url"><img src="images/20240121_124842.jpg" align="center" height=95% width=95% ></a>|<a href="url"><img src="images/20240121_124848.jpg" align="center" height=90% width=90% ></a>
<a href="url"><img src="images/20240121_124854.jpg" align="center" height=95% width=95% ></a>|<a href="url"><img src="images/20240121_125012.jpg" align="center" height=90% width=90% ></a>

### Enclosure

[Display Enclosure ESP32-3248S035](https://cults3d.com/:1482031)

### Credits
- [CYD-Klipper](https://github.com/suchmememanyskill/CYD-Klipper)
- [GT911 driver](https://github.com/TAMCTec/gt911-arduino)
- [xtouch](https://github.com/xperiments-in/xtouch)
- [ESP32-Cheap-Yellow-Display](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display)
