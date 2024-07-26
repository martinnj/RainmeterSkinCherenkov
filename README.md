
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
