# BTT-SKR-3-Taz5-Klipper-Printer.cfg
This is my printer.cfg for klipper on the Taz5 using the BTT SKR 3 V3

I used the BigTreeTech SKR 3 V3 with TMC 2209 stepper drivers to bring my old Lulzbot TAZ 5 back to life as a more modern machine. 
The machine printed well stock, but I wanted more control over it, which is why I chose to run Klipper to print faster and with better quality.

I struggled through creating a printer.cfg for hours before I got it working, so I am going to link my printer.cfg here and a bit more info so not everyone has to go through what I did.


On my Raspberry Pi, I am running Mainsail 32-bit. This is super easy to download with the Raspberry Pi Imager. 
Make sure to use a high-quality microSD card if you want it to be reliable. These things have a habit of randomly dying.

I used this as my base printer.cfg and modified it to fit my needs.
https://github.com/Klipper3d/klipper/blob/master/config/generic-bigtreetech-skr-3.cfg

I added a StealthChop to the printer.cfg in the TMC 2209 driver section. There are downsides to this, read here: https://github.com/Klipper3d/klipper/blob/master/docs/TMC_Drivers.md#setting-spreadcycle-vs-stealthchop-mode 

This video is great for getting started with Klipper. The Klipper docs are also great.
https://youtu.be/Df8-7zcwiUc?si=xpckIoQlwgI-z_Hh

