Kernel 3.12
===========

Kernel 3.12.0-rc2 (Bone patchset 2) for BeagleBone boards.

Status
======

Tested
------
 * I2C: not working
 * MMC: mmc1 working, mmc2 working
 * USB host: working, replugging needs ```lsusb``` to pick new devices, unless you use a hub in between
 * USB gadget: working

Not tested
----------
 * SPI: working [\[1\]][1]
 * LCDC: not-capebus has support for lcd3, lcd4, lcd7 and dvi capes [\[1\]][1]
 * TS: working [\[1\]][1]
 * ADC: not tested [\[1\]][1]
 * PWM: ehrpwm and ecap working [\[1\]][1], no sysfs entries
 * PMIC: working [\[1\]][1]
 * PMIC PWM: working [\[1\]][1], kills ethernet
 * CPUfreq: working [\[1\]][1]
 * Capes: DVI, LCD3, LCD4, LCD7, geiger and weathercape are functional [\[1\]][1], but need tweaking
 * Audio: working [\[1\]][1]
 * HDMI audio: not working [\[1\]][1]
 
 [1]: http://github.com/beagleboard/kernel/tree/3.12     "Beagleboard.org Kernel - 3.12 - Github"
