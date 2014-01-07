Kernel 3.8
==========

Kernel 3.8.13 (Bone patchset 35) for BeagleBone boards

Status (needs to be updated)
============================

 * I2C: working
 * MMC: mmc1 working, mmc2 working
 * USB host: working, replugging needs ```lsusb``` to pick new devices, unless you use a hub in between
 * USB gadget: working

> 

 * SPI: untested (reported as working [\[1\]][1])
 * LCDC: untested (reported as working [\[1\]][1])
 * TS: untested (reported as working [\[1\]][1])
 * ADC: untested (reported as working [\[1\]][1])
 * PWM: untested (ehrpwm and ecap reported as working [\[1\]][1])
 * PMIC: untested (reported as working [\[1\]][1])
 * PMIC PWM: untested (reported as working [\[1\]][1] but kills ethernet)
 * CPUfreq: untested (reported as working [\[1\]][1])
 * Capes: untested (almost all reported as working [\[1\]][1])
 * Audio: untested (reported as working [\[1\]][1])
 * HDMI audio: untested (reported as working [\[1\]][1])
 
Bootlog errors (needs to be updated)
====================================

No major faults found. Kernel is stable.


[1]: http://github.com/beagleboard/kernel/tree/3.8     "Beagleboard.org Kernel - 3.8 - Github"
