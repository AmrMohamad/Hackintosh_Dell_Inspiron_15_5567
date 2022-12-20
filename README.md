# EFI for Dell Inspiron 15 5567 using OpenCore

This repository contains the EFI folder for a successful hackintosh installation of macOS Big Sur or Monterey and the ability to update to Ventura on a Dell Inspiron 15 5567 laptop with an Intel 7th generation i7 processor.

___

## Laptop Specifications

___

## Installation

1. Download the latest version of OpenCore from the official website (<https://github.com/acidanthera/OpenCorePkg>).
1. Create a bootable USB drive using OpenCore and Use EFI-OC-for-KabyLake-PreInstall in this repository to make sure that macOS installation succeeded by renaming it to EFI and paste to USB EFI partition
1. By default, macOS will setup freshly formatted drives with 200MB. then by using <a href="https://github.com/corpnewt/MountEFI">MountEFI</a> mount that partition and paste EFI-for-booting folder and rename it to EFI

## Working Components

- Intel 7th generation i7 processor
- Display
- Audio
- Ethernet
- WiFi and Bluetooth (using a compatible PCIe card)
- USB ports
- Keyboard and touchpad

## Not Working

- Graphics acceleration (using Intel UHD 620)

## Credits

- The OpenCore team (https://github.com/acidanthera/OpenCorePkg)
- The OpenCore installation guide (https://dortania.github.io/OpenCore-Install-Guide/)
- The hackintosh community (https://www.tonymacx86.com/)
