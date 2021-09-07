# MSI GF63 8RD - OpenCore Files
##  Important Information - DEVICE DETAILS
|Title|Info|
|-|-|
|Model|GF63 8RD|
|BIOS Version|E16R1IMS.10D|
|CPU|Intel Core I7 8750H (Coffe Lake - H)|
|Graphics|Intel UHD 630 + NVIDIA GTX 1050Ti (Disabled)|
|Wi-Fi|Intel Wi-Fi Card|
|Ehternet|QCA8171|
|Audio|Realtek ALC269|
## Important Information - FIRSTLY README PLEASE
- DSDT.AML extract from BIOS Version of E16R1IMS.10D. If you use another bios version, maybe this EFI file not work correctly.
- If you use this EFI, please don't forget change SMBIOS details. (It's Dummy SMBIOS Inside. Pay particular attention to this, SMBIOS MacBookPro15,1 (Because HDMI Port Problems))
- CPU Power Management is complete with CPUFriendFriend.
## Important Information - BROKEN DEVICES
- NVIDIA GTX 1050Ti (Disabled for Battery Drain)
- All other devices are working. Tested and Passed :)
