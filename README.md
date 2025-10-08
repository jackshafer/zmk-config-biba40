# Biba40

![image16](images/PXL_20250408_155905966.jpg)
![image0](images/grey_and_purple_keycaps2.jpg)
![image13](images/PXL_20250227_221220365.PORTRAIT.ORIGINAL.jpg)
![image1](images/custom_pcb.jpg)
![image2](images/shield_and_switches.jpg)
A 40% Split Ortholiner wireless keyboard powered by ZMK.

* Keyboard Maintainer: [Daniel Biba](https://github.com/danbiba)
* Hardware Supported: nice!nano v2, Supermini NRF52840
* Hardware Availability: 3D Printable
* Buy your own : https://bibakeyboards.com/

## Keymap
### Default Layer
![image3](images/biba40_def.jpg)
### Lower Layer
![image4](images/biba40_raise.jpg)
### Raise Layer
![image5](images/biba40_lower.jpg)
### Adjust Layer
![image6](images/biba40_adjust.jpg)
### Function Layer
![image7](images/biba40_function.jpg)

## Setup
Clone the repository located at https://github.com/danbiba/zmk-config-biba40

Compile the firmware using Github actions. This will produce 3 files:

* biba40_left-nice_nano_v2-zmk.uf2
* biba40_right-nice_nano_v2-zmk.uf2
* settings_reset-nice_nano_v2-zmk.uf2

## Bootloader

Enter the bootloader in 3 ways:

* Lower + 0,3 (for the left board)
* Raise + 5,3 (for the right board)
* Short out pins RST and GND on the nice!nano v2

[View the BIBA40 V2 Build Guide](Build_Guide.md)
