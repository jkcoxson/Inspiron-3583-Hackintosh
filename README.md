# Inspiron-3583-Hackintosh
This laptop is a Hackintosher's dream. Inexpensive, relatively new, and contains **two drive bays!** Yes, my friends, dualbooting Windows and MacOS has never been easier in a laptop, so let's get started.
## Issues
This is pretty good, but let's get the details.
- [x] Touchscreen
- [x] Touchpad Gestures
- [ ] Intel WiFi **This will probably never work, so replace with DW1560**
- [ ] HDMI Audio
- [ ] HDMI Video
- [x] Audio jack 
- [ ] Function Keys (Workaround with Key Elements)
- [x] Sleep
- [x] Power Management
- [x] USB Ports
- [x] Handoff (Using DW1560)
- [x] iMessage
- [x] Airdrop (Using DW1560)
- [x] Unlock with Apple Watch

## Use
Download OpenCore onto one flash drive, and replace the files in this repo. You must enter your own serial number and ID for use. Use another flash drive to flash MacOS onto it. [Guide](https://support.apple.com/en-us/HT201372). Everything should be dandy with the install.

## Workarounds
We need two workarounds currently to get things in shape. 
1. Download Karibiner Elements and set the function keys to the functions that they belong in. Also, change the the tilde key and the pipe key, as they are swapped.
2. ~~Download the files from Jack_Workaround and place jackfix in your home folder and Jack\ Fix in /usr/local/bin. Whenever the headphone jack doesn't work, just open terminal and run ./jackfix~~ Now implemented properly!

## Unlock with Apple Watch
You must have a wireless chip that works out of the box for Apple Watch Unlock. 
Even on a real Mac this is a pain! It may just work to press the box, but what did it for me was flushing the routes. 

## I do not condone piracy. I am not responsible for what this is used for. 
## Thanks to everyone who developed the actual software, I just compiled it for use with this machine.
