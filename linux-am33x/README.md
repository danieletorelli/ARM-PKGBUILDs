Kernel 3.12
===========

Kernel 3.12.0-rc2 (Bone patchset 2) for BeagleBone boards

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
 * SPI: untested (reported as working [\[1\]][1])
 * LCDC: untested (not-capebus has support for lcd3, lcd4, lcd7 and dvi capes [\[1\]][1])
 * TS: untested (reported as working [\[1\]][1])
 * ADC: untested (reported as untested [\[1\]][1])
 * PWM: untested (ehrpwm and ecap reported as working [\[1\]][1] but no sysfs entries)
 * PMIC: untested (reported as working [\[1\]][1])
 * PMIC PWM: untested (reported as working [\[1\]][1] but kills ethernet)
 * CPUfreq: untested (reported as working [\[1\]][1])
 * Capes: untested (DVI, LCD3, LCD4, LCD7, geiger and weathercape are functional [\[1\]][1] but need tweaking)
 * Audio: untested (reported as working [\[1\]][1])
 * HDMI audio: untested (reported as not working [\[1\]][1])
 
[1]: http://github.com/beagleboard/kernel/tree/3.12     "Beagleboard.org Kernel - 3.12 - Github"
