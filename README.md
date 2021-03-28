# Opencore-EFI
# Lenovo ThinkPad L480 

Hackintosh using OpenCore 0.6.7 EFI files

# Specs:
1. i7-8550u + UHD 620
2. 8gig RAM
3. 1TB Seagate HDD
4. Intel 8625 WiFi

# What's working:
1. WiFi + Bluetooth
2. Trackpad + TrackPoint + Gestures
3. IGPU Acceleration
4. Backlight + Brightness Keys (F5, F6)

# What's not working / not tested:
1. WWAN
2. Fingerprint scanner
3. Ethernet (will work easily, i just didn't bother)
4. Smart Card Reader
5. microSD reader
6. Battery status/indicator

# Misc
1. i will be removing my platforminfo for security reasons therefore use GenSMBIOS to plug fresh values into config.plist
2. if anyone can make the battery status indicator to work kindly make a pull request so that i can add it for everyone else
