# OCEliteBook850G3
OpenCore EFI folder for the HP EliteBook 850 G3 on [OpenCore 0.7.1](https://github.com/acidanthera/OpenCorePkg)

Clone and copy to your EFI folder. Don't forget to add your own [SMBIOS](https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#macbook-pro). ([ProperTree](https://github.com/corpnewt/ProperTree) is advised)
I used SMBIOS of MacBookPro13,3, however; I would advise using MacBookPro13,1 or MacBookPro13,2 since they are using Skylake U processors.
```
git clone https://github.com/lucasrequile/OCEliteBook850G3
```
Everything is working as far as I'm aware, including native Intel [Bluetooth](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) and [WiFi](https://github.com/OpenIntelWireless/itlwm) support. I am running on the latest MacOS Big Sur 11.4 at the moment.
