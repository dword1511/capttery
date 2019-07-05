# Capttery Code Release

Resources will be gradually added as submodules. Please be patient...

To check out the whole workspace, run

```
git clone --recurse-submodules https://github.com/dword1511/capttery.git
```

## TODOs

* Firmware: Voltage monitor
* PCB: Voltage monitor
* Simulation files from Sidharth
* Schematics for the high-voltage probe

## Done

The `inverter` folder contains the firmware and PCB for the half-bridge driver that provides 1 MHz input to the transmitter matching network.

The `showcase_ble` folder contains the firmware and related information for the BLE sensing station showcase scenario.

The `showcase_uwb` folder contains the firmware and related information for the UWB localization tag.

The `showcase_uwb_app` folder contains the Decawave UWB localization application for Linux PC.

The `showcase_power` folder contains [Monsoon Power Monitor](https://www.msoon.com/lvpm-software-download) screenshot for both showcase applications.
See the upper-right corner for statistics. Original trace were not preserved.

The `spice` folder contains LTSpice schematics for TX and RX circuit-level simulations.
The schematics contain brief instructions, while the detailed versions are under preparation.
