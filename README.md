# Opencore-EFI
# Lenovo ThinkPad L480 

Hackintosh using OpenCore 0.6.7 EFI files

# Specs:
i7-8550u + UHD 620
8gig RAM
1TB Seagate HDD
Intel 8625 WiFi

# What's working:
WiFi + Bluetooth
Trackpad + TrackPoint + Gestures
IGPU Acceleration
Backlight + Brightness Keys (F5, F6)

# What's not working / not tested:
WWAN
Fingerprint scanner
Ethernet (will work easily, i just didn't bother)
Smart Card Reader
microSD reader
Battery status/indicator

# Misc
1. i will be removing my platforminfo for security reasons therefore use GenSMBIOS to plug fresh values into config.plist
2. if anyone can make the battery status indicator to work kindly make a pull request so that i can add it for everyone else
