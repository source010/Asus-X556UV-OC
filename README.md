# Asus X556UV OpenCore
## Screenshots from MacOS Catalina 10.15.6
![Screen Shot 2022-11-09 at 01 10 12](https://user-images.githubusercontent.com/78357560/200655523-36c3f191-75af-451a-b143-8f41165a3c59.png)
![Screen Shot 2022-11-09 at 01 12 04](https://user-images.githubusercontent.com/78357560/200655539-d4fc83b1-ff96-4ff0-87b4-9a14cb496e13.png)
May work on MacOS Big Sur but without AirPortAtheros40.kext
<br>

## Laptop Specifications <br>

| Device  | Name |
| ------------- | ------------- |
| CPU  | Intel Core I3 6100  |
| GPU  | Intel HD Graphics 520, Nvidia Geforce MX920 (not used)  |
| RAM  | 4GB 2x (8GB In Total) |
| LAN  | Realtek RTL8111 |
| WiFi, BlueTooth  | Qualcom Atheros 956X (9565) |
| USB  | 2 Slots |
| Trackpad  | Elan 1000 Trackpad I2C |
| Audio  | alc255 (used layout-id 27) |


## To Do List
 - [x] Make system bootable 
 - [x] Get audio to work
 - [x] Fix Graphics
 - [x] Fix Brightness
 - [x] Fix All USB Ports
 - [x] Try Successfully jailbreak an iPhone
 - [x] Test HDMI
 - [ ] Get Trackpad to work
 - [ ] Test 'Sleep'
 - [ ] Add a GUI for Booter

## Kexts used
- AirPortAtheros40.kext		
- SMCProcessor.kext
- AppleALC.kext			
- USBMap.kext
- AsusSMC.kext			
- VerbStub.kext
- CPUFriend.kext			
- VirtualSMC.kext
- CPUFriendDataProvider.kext	
- VoodooI2C.kext
- HibernationFixup.kext		
- VoodooI2CELAN.kext
- Lilu.kext			
- VoodooPS2Controller.kext
- RealtekRTL8111.kext		
- WhateverGreen.kext
- SMCBatteryManager.kext

| Confirmed to work macOS version  | Unconfirmed to work macOS version |
| ------------- | ------------- |
| Mojave / 10.14  | Sierra / 10.12  |
| Catalina / 10.15  | High Sierra / 10.13  |
| Big Sur / 11  | Monterey / 12 |
