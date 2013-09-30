Kernel 3.8
==========

Kernel 3.8.13 (Bone patchset 28) for BeagleBone boards

Status
======

Tested
------
 * I2C: working
 * MMC: mmc1 working, mmc2 working
 * USB host: working, replugging needs ```lsusb``` to pick new devices, unless you use a hub in between
 * USB gadget: working

Not tested
----------
 * SPI: working [\[1\]][1]
 * LCDC: working [\[1\]][1]
 * TS: working [\[1\]][1]
 * ADC: working [\[1\]][1]
 * PWM: ehrpwm and ecap working [\[1\]][1]
 * PMIC: working [\[1\]][1]
 * PMIC PWM: working [\[1\]][1], kills ethernet
 * CPUfreq: working [\[1\]][1]
 * Capes: almost all [\[1\]][1], check firmware/capes
 * Audio: working [\[1\]][1]
 * HDMI audio: working [\[1\]][1]
 
[1]: http://github.com/beagleboard/kernel/tree/3.8     "Beagleboard.org Kernel - 3.8 - Github"
