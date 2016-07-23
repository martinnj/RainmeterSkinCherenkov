# RainmeterSkinCherenkov
A rainmeter skin that shows essential information about the computer it is running on.


# Requirements
[OpenHardwareMonitor](http://openhardwaremonitor.org/) must be running for the
plugin to gather CPU temperature as well as GPU information.

# Installation
Simply run the relevant .rmskin file found in the root of the project. This will
automatically unpack the skin and the needed plugin
(OpenHardwareMonitorPlugin.dll).

Note: The V2 rmskin package does not contain the plugin itself since Rainmeter
won't allow me to create the package without also shipping the 32-bit version
of the plugin. Which I don't have around :)

# Adaptation
The skin is easy to adapt, in the top of the
```Flanker\Cherenkov\Cherenkov.ini```/```Flanker\Cherenkov\CherenkovV2.ini``` file there is a section called
```variables```. These can all be changed to retheme the skin or to allow for
different hardware. (It will currently only show the hardware I use.)
