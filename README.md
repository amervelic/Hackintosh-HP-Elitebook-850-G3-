# Hackintosh HP EliteBook 850 G3

## macOS Ventura 13.0 - OpenCore version 0.8.5

![Ventura](/images/ventura.jpeg)

![](https://img.shields.io/github/issues/amervelic/Hackintosh-HP-Elitebook-850-G3-)
![](https://img.shields.io/github/forks/amervelic/Hackintosh-HP-Elitebook-850-G3-)
![](https://img.shields.io/github/stars/amervelic/Hackintosh-HP-Elitebook-850-G3-)

### Note for clean install

- Change SMBIOS to Macbook Pro 14,1
- SSD format to APFS (for install to external SSD)
- After install back to SMBIOS 13,2 and flag -no_compat_check
### Corresponding kexts:

- Intel HD 520 graphics - [WhateverGreen](https://github.com/acidanthera/WhateverGreen), AAPL,ig-platform-id = 00001B59 , device-id = 16590000
- Conexant CX20724 ISST Audio - [ AppleALC](https://github.com/acidanthera/AppleALC), , layout ID 13
- Intel AC 8260 WiFi+BT - [AirportItlwm Alpha](https://github.com/OpenIntelWireless/itlwm/releases) + [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)

- Intel I219-LM Ethernet - [IntelMausiEthernet](https://github.com/acidanthera/IntelMausi)
- Battery percentage - [SMCBatteryManager](https://github.com/acidanthera/VirtualSMC),[ECEnabler](https://github.com/1Revenger1/ECEnabler)

- Keyboard and mouse nipple - [VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2)

- SMBus trackpad - [VoodooRMI](https://github.com/VoodooSMBus/VoodooRMI)

- Screen brightness via SSDT-PNLF

- Fn hotkeys (mostly)

- DisplayPort and VGA outputs

### Special thanks:
- acidanthera for [OpenCore](https://github.com/acidanthera/OpenCorePkg) and half the kexts here 
- For detaiils [koktagon](https://github.com/koktagon/hackintosh-840-G3-Catalina-DQ/tree/Monterey)