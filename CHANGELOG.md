# Changelog

All notable changes to this project will be documented in this file.

## \[4.5.0] - 2026-10-16

### Changed

* Finalized the CEREPHYTE Rev. 4.2 schematic architecture in KiCad.

* Updated the power supply architecture to use an XL4015 buck converter (`U7`) configured for regulated 5 V output (`VDD`).

* Documented the 2S lithium-ion battery system, charging circuit (`U6`), BMS (`U5`), and INA219 power monitor (`U9`).

* Updated the documentation for the analog front-end, including dual CD4051B multiplexers, the AD620 instrumentation amplifier module, and OP07/TL081 active filtering stages.

* Documented the Arduino Uno and NodeMCU ESP-12E processing architecture and TXS0108E level-shifting interface.

* Documented ADS1115 analog-to-digital conversion through `AIN0`, using the default I²C address `0x48`.

* Documented the INA219 power monitor at I²C address `0x40`.

* Documented the MAX485 RS-485 communication interface and capacitive-touch user interface modules.

* Documented the analog and digital grounding architecture using `GNDA`, `GNDD`, and NetTies.

* Prepared the Rev. 4.2 schematic baseline for physical prototyping.

### Status

* Schematic revision: CEREPHYTE Rev. 4.2.

* Schematic design: Finalized in KiCad.

* Hardware implementation: Transitioning to physical protoboard assembly and testing.

* Firmware and software integration: In development.

### Notes

* Schematic finalization does not imply physical hardware validation.

* Power regulation, component compatibility, grounding, signal integrity, and acquisition performance remain subject to hardware testing.

## \[4.0.0] - 2026-08-03

### Added

* Initial public release of the CEREPHYTE hardware resources repository.

* Added KiCad design files, symbols, footprints, and supporting documentation.

* Added schematic and PCB resources under the project directories.

* Added licensing, attribution, and third-party documentation for public release.

### Changed

* Organized the repository structure for easier GitHub publication and review.

* Expanded project documentation to better describe the hardware resources included.

### Notes

* This repository is distributed under the CEREPHYTE Hardware License (CHL) v1.0.

* Third-party ESP8266 library files remain subject to their original CC BY-SA 4.0 license.
