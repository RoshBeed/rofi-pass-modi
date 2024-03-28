# rofi-pass-modi
Rofi modi to copy passwords to clipboard from password store

This script was update to function in a hybrid dmenu mode: it is first run without dmenu mode but then switches to dmenu mode.
The objective is to avoid conflicts between with potential passwords request windows and the rofi menu.

## Usage
Pass arguments through command line
```
rofi -show pass -modi pass:./rofi-pass-modi
```
or append to ```.config/rofi/config```
```
rofi.modi: 	pass:/<dir-to-rofi-pass-modi>/rofi-pass-modi
```
