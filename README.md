# HWSensors

HWSensors is a software bundle that includes drivers and applications that allow you to access information from hardware sensors available on your Mac.

FakeSMC is an open source SMC device driver/emulator developed by [netkas](http://netkas.org).

##### NOTE: FakeSMC & Plugins starting from v915 provide additional sensors information to HWMonitor on Macs. By installing FakeSMC on a real Mac you acknowledge that you know what you are doing and how to recover your system if something goes wrong.

## Notes about this fork by Dekson

A note about the contents of the download:
Debug/FakeSMC.kext - debug FakeSMC.kext + PlugIns (install for troubleshooting)
Release/FakeSMC.kext - release FakeSMC.kext + PlugIns (recommended install)

Debug/HWMonitor.app - debug version of kozlek's HWMonitor.app
Release/HWMonitor.app - release version of kozlek's HWMonitor.app (recommended)

SL/HWMonitor.app - release version of slice's HWMonitor.app, modified to
 work with kozlek's FakeSMC.kext.  Primarily for use on Snow Leopard, but
 will also work on ML or Lion.

To install:
- install FakeSMC.kext using Kext Wizard.
  (Note: if you had previously used slice's and have the various kexts 
   spread all over /S/L/E, be sure to remove them all)
- run HWMonitor.app and set it up to your preference.


## All repositories:

[SourceForge](https://sourceforge.net/projects/hwsensors),
[BitBucket](https://bitbucket.org/kozlek/hwsensors/overview),
[Assembla](https://www.assembla.com/code/fakesmc/git/nodes),
[GitHub](https://github.com/kozlek/HWSensors)

## Special thanks to:
netkas for fakesmc.  
slice for plugins and help in developing the project.  
usr-sse2 for help in development and first FakeSMC plugins idea and realization.  
Navi for investigation of numeric SMC values encoding/decoding and other useful stuff.  
droplets for testing.  
Michael Möller for OpenHardwareMonitor.  
The Real Deal & JrCs for French localization.  
RehabMan forced me using mutexes and other contributions to the project.  
Oliver Bolton for OBMenuBarWindow.  
Mozketo for LaunchAtLoginController.  
PHPdev32 for an idea to using NVRAM as storage for kext configuration.  
coercion for initial Haswell support.  
oswaldini @ www.osx86.org.pl for Polish translation.  
Matteo «Marchrius» Gaggiano for the enhanced about window with credits scroller and Italian translation.  
k3nny @ www.insanelymac.com for German translation.  
Bruce Allen for [smartmontools](http://www.smartmontools.org).   
Michael Robinson for Cocoa [Categories](https://github.com/faceleg/Cocoa-Categories).  
Stephane Sudre for Packages (packagesbuild).  
Andy Matuschak for Sparkle framework.  
Nouveau Project for nouveau linux driver (GeforceSensors base).  
Advanced Micro Devices and all contributors for AMD Radeon linux driver (RadeonSensors base).  
Joshua Nozzi for [JLNFadingScrollView](https://github.com/jnozzi/JLNFadingScrollView).  
Rheinfabrik for [RFOverlayScrollView](https://github.com/rheinfabrik/RFOverlayScrollView).  
Matteo Gaggiano for the enhanced about window with credits scroller.  
**HWSensors Project &copy; 2014 netkas, slice, usr-sse2, kozlek, navi, THe KiNG, RehabMan and others. All rights reserved.**
