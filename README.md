# No-AHCI-FIx-For-OSX
This is a fix for people without AHCI and only have ATA.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

NOTES:
- These Patches have only been tested on the Dell Optiplex 390 (Which has no AHCI)
------------------------------------------------------------------------------------

Installation Method for all Legacy Systems:
- 1: Get 2 USB's that are of higher capacity (Min=16GB) (Recommeneded: 32GB)
- 2: Use one USB as your Install USB and one as the drive you will be putting macOS on
- 3: Create your Installer with your own specified patches for your build
- 4: Boot Into the installer and install macOS onto the other USB
- 5: After Install has finished boot into macOS from your USB
- 6: Use a Kext Installler Utility (Kext Droplet) and install the kexts into the S/L/E Directory of your macOS USB (For Big Sur: Install into the L/E Directory
- 7: Reboot
- 8: Boot into your macOS USB and verify that your internal HD is detected
- 9: Use Carbon Copy Cloner to Clone your USB to your Intenal HD
- 10: When it's done you can eject all USB and reboot
- 11: macOS should be on your Internal Drive and should be patched with the No AHCI from before

 Enjoy your macOS Installation!
