# Hackintosh Dell Inspiron 3583
This laptop is a Hackintosher's dream. Inexpensive, relatively new, and contains **two drive bays!** Yes, my friends, dualbooting Windows and MacOS has never been easier in a laptop, so let's get started.
## Dell Inspiron 15 3583 specs
  * Dell Inspiron 15 Full Specifications:
    - Intel i7-8565U (Whiskey Lake);
    - 16GB RAM;
    - SSD SATA Kingstone 240GB;
    - Display FullHD;
    - 2 USB 3.0, 1 USB 2.0;
    - Card Reader;
    - Phone jack;
    - Webcam;
    - Realtek ALC236;
    - Intel Wireless AC9462;
    - Ethernet Realtek RTL810xE FE;
## Issues
This is pretty good, but let's get the details.
- [x] Touchscreen
- [x] Touchpad Gestures
- [x] Intel WiFi **Some users have reported that using Airportitlwm kexts will enable wifi, but I replaced my card with a DW1560. See #2**
- [x] HDMI Audio
- [x] HDMI Video
- [x] Audio jack (No mic in)
- [ ] Function Keys (Workaround with Key Elements)
- [x] Sleep
- [x] Power Management
- [x] USB Ports
- [x] Handoff (Not tested)
- [x] iMessage
- [x] Airdrop (Not tested)
- [ ] Unlock with Apple Watch (Only switching WiFi card, not Intel Wifi)

## Use
Download OpenCore onto one flash drive, and replace the files in this repo. You must enter your own serial number and ID for use. Use another flash drive to flash MacOS onto it. [Guide](https://support.apple.com/en-us/HT201372). Everything should be dandy with the install.

## Workarounds
We need two workarounds currently to get things in shape. 
1. Download Karibiner Elements and set the function keys to the functions that they belong in. Also, change the the tilde key and the pipe key, as they are swapped.

## Unlock with Apple Watch
You must have a wireless chip that works out of the box for Apple Watch Unlock. 
Even on a real Mac this is a pain! It may just work to press the box, but what did it for me was flushing the routes. 

## Intel WiFi
You might be able to use the built in WiFi card -> https://github.com/OpenIntelWireless/itlwm

## I do not condone piracy. I am not responsible for what this is used for. 
## Thanks to everyone who developed the actual software, I just compiled it for use with this machine.
