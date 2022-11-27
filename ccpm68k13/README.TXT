CompuPro CP/M-68K v1.3 System Masters
=====================================

In November, 2022, the CompuPro CP/M-68K v1.1 System Master disks were
recovered from orignal 8" floppies and archived at:
https://bitsavers.org/bits/Compupro/ 

CP/M-68K v1.3 for CompuPro was created using the CompuPro-specific loader
and BIOS from the v1.1 disks, ported to the original CP/M-68K v1.3
distribution from:
http://cpm.z80.de/download/68kv1_3.zip

CompuPro CP/M-68K v1.3 is distributed per the license here:
http://www.cpm.z80.de/license.html

This distribution was created using the SIMH/AltairZ80 simulator
(https://github.com/open-simh/simh) using the following CompuPro
components:

CompuPro 68000 CPU Board
CompuPro System Support Board
CompuPro DISK1A floppy disk controller
CompuPro DISK2 hard disk controller
1MB of RAM

This distribution contains boot disks for the 68000 and 68010 CPUs:

ccpm68k13_d1.imd       Boots on the 68000 CPU.
ccpm68k13_d2.imd       Boots on the 68010 CPU.

SIMH configuration files are provided for both 68000 and 68010:

ccpm68k13.ini          SIMH Configuration file for 68000 CPU.
ccpm68k13_010.ini      SIMH Configuration file for 68010 CPU.

The disk image files can be written to floppies using Dave Dunfield's
ImageDisk software.

This distribution has not been tested on real hardware. 

Download link: https://github.com/hharte/altairz80-packages/tree/main/ccpm68k13
