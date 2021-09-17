# clover-ga-x79-ud5-i7-3970X-rx580
Hackintosh GA-X79-UD5 with F14e BIOS, tested to work Catalina.  Latest Clover 5139

This repository is the contents of /EFI folder on EFI boot partition .

Board: GA-X79-UD5 with BIOS version F14e

CPU: i7-3970X Sandy Bridge-E

RAM: 64 GB 1333 MHz DDR3

GPU: Radeon RX 580 8GB with 2 x DELL P2418D on DisplayPort and 1x DELL P2418D on HDMI

SMBIOS: Using iMacPro1,1

This is the result of quite a lot of work and upkeep.  Oh, and lack of sleep.   

All my USB2 and USB3 ports are working.  I also have internal Bluetooth and Apple WIFI cards installed with just natively work.  

- This currently has Clover 5139 and latest lilu, whatevergreen etc.  And necessary kexts for X79 power management
- The ssdts are from serveral sources. Note the 1 specific to i7-3970X processor which you may need to change in your own situation.
- I have obfuscated the board serial numbers and SMBIOS. You would need to make your own.

Some of the gotchas to be careful of :

- BIOS settings.   Make sure that you have EFI boot enabled
- Will add BIOS settings here at a later date.

If anyone has managed to scale up to OpenCore or Big Sur with this board, kindly let me know.

