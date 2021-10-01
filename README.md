# plutosdr-m2k-drivers-win

Windows USB drivers for PlutoSDR & M2k

Latest Release : [![GitHub release](https://img.shields.io/github/release/analogdevicesinc/plutosdr-m2k-drivers-win.svg)](https://github.com/analogdevicesinc/plutosdr-m2k-drivers-win/releases/latest)

Supported Hardware
* ADALM-PLUTO
* ADALM-2000
* Generic IIO/Serial Console device using VID_0456&PID_B671

Release History
* v0.5
  * Fix package installer on Windows 32-bit
* v0.6 (No need to update from v0.5)
  * Add reference to M2k onto the wizard pages (no functional changes)
  * Force DPInst to install the driver even if the driver that is currently installed is a better match than the new driver
* v0.7
  * Removed language nodes from dpinst.xml, this should fix this Error: "The current language is not supported by the Device Driver Installation Wizard)"
* v0.8
  * New device support

