Here's some basic instructions on compiling VBAGX. You don't need to be a programmer to follow these instructions but you should have some basic computer know-how. There's a few reasons you might want to do this:

  1. To use the latest version of the emulator (note that beta versions may be unstable)
  1. To access roms/saves from Windows File Sharing (SMB), without needing an SD card - just edit vbaconfig.cpp
  1. To make your own custom changes

# Instructions #

  1. Ensure that you have [devkitPPC r24 and libogc 1.8.7](http://www.devkitpro.org) or higher installed. If you have an older version, completely uninstall it first.
  1. Download and copy the [ported libraries](http://sourceforge.net/projects/devkitpro/files/portlibs) to your PPC portlibs folder (on Windows this is c:\devkitPro\portlibs\ppc)
  1. Download the source from [SVN](http://code.google.com/p/vba-wii/source/checkout).
  1. Run Programmer's Notepad (installed with devkitPro)
  1. Find the Makefile from the source you downloaded. Click Tools > Make.
  1. You're done!