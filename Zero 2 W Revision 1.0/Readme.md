
# PCB Front Image
![24561703225898_ pic](https://github.com/josthlee/RaspberryPi/assets/154501794/accdfc85-41b7-4e2c-9616-edd790e01f1b)

# PCB Back Image
![24571703225901_ pic](https://github.com/josthlee/RaspberryPi/assets/154501794/aab30295-d049-4c35-9969-3214df9fd52e)

# GPIO Pin Layout
![GPIO-Pinout-Diagram-2](https://github.com/josthlee/RaspberryPi/assets/154501794/463fd304-32f9-4e23-82b7-95522199f1ed)

# Raspberry Pi OS

## Download Raspberry Pi OS

https://www.raspberrypi.com/software/operating-systems/
![24511703212678_ pic](https://github.com/josthlee/RaspberryPi/assets/154501794/63d6aaa9-2a5f-42d1-9a30-90124a6ac664)

## Write image to SD card
![Screenshot 2023-12-22 at 10 39 03](https://github.com/josthlee/RaspberryPi/assets/154501794/3aeb4dfc-cf77-4b08-b9aa-d8978025c0aa)

# pinout command

pi@raspberrypi:~ $ pinout 

```
Description        : Raspberry Pi Zero2W rev 1.0
Revision           : 902120
SoC                : BCM2837
RAM                : 512MB
Storage            : MicroSD
USB ports          : 1 (of which 0 USB3)
Ethernet ports     : 0 (0Mbps max. speed)
Wi-fi              : True
Bluetooth          : True
Camera ports (CSI) : 1
Display ports (DSI): 0

,--oooooooooooooooooooo---.
|  1ooooooooooooooooooo J8|
---+     +---+  PiZero2W  c|
 sd|     |SoC|   Wi V1.0  s|
---+     +---+   Fi       i|
| hdmi            usb pwr |
`-|  |------------| |-| |-'


J8:
   3V3  (1) (2)  5V    
 GPIO2  (3) (4)  5V    
 GPIO3  (5) (6)  GND   
 GPIO4  (7) (8)  GPIO14
   GND  (9) (10) GPIO15
GPIO17 (11) (12) GPIO18
GPIO27 (13) (14) GND   
GPIO22 (15) (16) GPIO23
   3V3 (17) (18) GPIO24
GPIO10 (19) (20) GND   
 GPIO9 (21) (22) GPIO25
GPIO11 (23) (24) GPIO8 
   GND (25) (26) GPIO7 
 GPIO0 (27) (28) GPIO1 
 GPIO5 (29) (30) GND   
 GPIO6 (31) (32) GPIO12
GPIO13 (33) (34) GND   
GPIO19 (35) (36) GPIO16
GPIO26 (37) (38) GPIO20
   GND (39) (40) GPIO21

For further information, please refer to https://pinout.xyz/
```
