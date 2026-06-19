# garagepro_sdk
This is a repository for hosting GaragePro SDK library for enterprise clients. Please contact us for further information at fix@carpm.in

## Release Notes (Only for stable versions)

### Version 6 (0.0.6)
First release of the GaragePro SDK. This contains two features - Read Fault Codes and Clear Fault Codes in any vehicle (Only full scan allowed)

### Version 11 (0.1.1)
Added feature - Live Data in any vehicle

### Version 15 (0.1.5)
Fixed live data bugs and tata decoding

### Version 17 (0.1.7)
Added feature - Module wise Read Fault Codes and Clear Fault Codes

### Version 19 (0.1.9)
Added feature - Vin Check feature, can be run before scan, clear or live scan

### Version 21 (0.2.1)
Added feature - Added differentiation in Basic Live Data commands and Advanced Live Data commands. Now user has to select either basic or advanced commands to run.

### Version 22 (0.2.2)
Added feature - Added battery voltage command in live scan and in all module scan

### Version 24 (0.2.4)
Added feature - Added selectScanner() function to manually select the scanner

### Version 25 (0.2.5)
Added feature - Auto detect ECU for heavy commercial vehicles in Live Data scan


### Version 26 (0.2.6)
Live data basic command headers issue fixed.

### Version 28 (0.3.1)
Added feature - Client-managed connection (BYO connection) mode: the host app handles Bluetooth permissions, scanning, pairing and the connection (BLE GATT or classic), and hands it to the SDK via the new GProDeviceConnection. All flows (VIN, scan, clear, live scan) supported with no SDK dialogs - every result/failure arrives via callbacks. Requires the master credentials issued for this integration.
Added feature - Per-module completion callback (GProModuleScanListener) with locally decoded fault codes (Current/Pending/History, warning-light flag) and vehicle-level MIL ON/OFF - available in both connection modes.
Security - The SDK artifact is now fully obfuscated (R8).

### Version 29 (0.3.2)
See https://github.com/zymbia-carpm/garagepro_sdk/releases/tag/v0.3.2

### Version 30 (0.3.3)
See https://github.com/zymbia-carpm/garagepro_sdk/releases/tag/v0.3.3
