# ErgoFlowWingA Firmware

This repository contains firmware files for the **ErgoFlow Wing-A** keyboard running on Nice!Nano v2 controllers.  

## How to Flash Firmware
1. Go to the **Actions** tab and download the required files.  
2. Connect the controller to your computer.  
3. Double-press the **RESET** button to put the microcontroller into bootloader mode.  
4. Copy the corresponding `.uf2` file onto the controller:  

- `settings_reset-nice_nano_v2-zmk.uf2` — resets the controller to default settings  
- `ergoflowwinga_left-nice_nano_v2-zmk.uf2` — firmware for the **left half** of the keyboard  
- `ergoflowwinga_right-nice_nano_v2-zmk.uf2` — firmware for the **right half** of the keyboard  

## Notes
- It’s recommended to perform a reset (`settings_reset`) before flashing the left and right halves.  
- Make sure you flash the correct firmware file to the correct controller (left ↔ right).  
