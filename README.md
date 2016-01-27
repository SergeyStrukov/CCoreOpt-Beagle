CCoreOpt-Beagle
===============

gcc toolset for CCore on BeagleBone Black

Copy opt.7z to the cygwin64 root directory. Unpack. Your will get the subdirectory /opt with the toolset.
Use it with the CCore target BeagleBoneBlack to build CCore applications.

--- CCore-2-xx ---------------------------

The directory CCore-2-00 contains the opt.7z in several volumes. 
This /opt contains both host and cross gcc-5.2.0 to be used with CCore-2-xx.

--- Boot ---------------------------------

These files can be copied on a Micro SD card on the first partition.
This partition must be formatted as FAT32 and marked bootable.
Use this card to boot the board. After the two-stage bootloader the CCore PTP Boot server is up.
You can see the Boot server messages on the monitor, attached to the board.

------------------------------------------
