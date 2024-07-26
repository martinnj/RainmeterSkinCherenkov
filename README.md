
# Rainmeter Skin - Cherekonv V4

A rainmeter skin that shows essential information about the computer it is
running on.

## Requirements

[HWiNFO64](https://www.hwinfo.com/) must be running, and the "Shared memory
support" setting must be enabled. This is used to gather the following data:

 - CPU Max Core Temprature.
 - GPU Core Load.
 - GPU Memory Usage.
 - GPU Temperature.

## Installation

Run the `CherenkovV4.x.rmskin` file and Rainmeter should automatically install
the skin as well as the plugin necesarry for getting the data from HWiNFOs
shared memory.

## Configuration

### Looks

Edit the skins `ini` file through Rainmeter. (Right click and select `edit` once
loaded.) and configure the colors and variables as necesarry. All the variables
are collected in the top of the file.

### Hardware

Unlike OpenHardwareMonitor where you just enter the name of the hardware and the
entry you want, HWiNFO used addresses so is a little more involved.

The default values should work for any single CPU, single GPU system.

n. Make sure HwiNFO is running with shared memory enabled.
n. Download and run `HWiNFOSharedMemoryViewer.exe`.
n. Use it to find the addresses for the hardware/sensor you want.
n. Enter the addresses in the top of the `.ini` file for the skin.

## Legacy versions

A rainmeter skin that shows essential information about the computer it is
running on.


### Requirements

[OpenHardwareMonitor](http://openhardwaremonitor.org/) must be running for the
plugin to gather CPU temperature as well as GPU information.

### Installation

Simply run the relevant .rmskin file found in the root of the project. This will
automatically unpack the skin and the needed plugin
(OpenHardwareMonitorPlugin.dll).

Note: The V2 rmskin package does not contain the plugin itself since Rainmeter
won't allow me to create the package without also shipping the 32-bit version
of the plugin. Which I don't have around :)

### Adaptation

The skin is easy to adapt, in the top of the
```Flanker\Cherenkov\Cherenkov.ini```/```Flanker\Cherenkov\CherenkovV2.ini```
file there is a section called ```variables```. These can all be changed to
theme the skin or to allow for different hardware. (It will currently only show
the hardware I use.)
