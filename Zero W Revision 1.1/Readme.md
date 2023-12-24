
# PCB Front Image
![24541703225894_ pic](https://github.com/josthlee/RaspberryPi/assets/154501794/c6a46061-e85b-4d9f-87b4-ce233735a89f)

# PCB Back Image
![24551703225896_ pic](https://github.com/josthlee/RaspberryPi/assets/154501794/040ecc8d-0a39-4dbb-9406-5872d7048e4f)

# GPIO Pin Layout
![GPIO-Pinout-Diagram-2](https://github.com/josthlee/RaspberryPi/assets/154501794/463fd304-32f9-4e23-82b7-95522199f1ed)

# Raspberry Pi OS

## Download Raspberry Pi OS

https://www.raspberrypi.com/software/operating-systems/
![292346888-e52e9271-6f5e-4f2f-a8ad-b7cf02eb6cd1](https://github.com/josthlee/RaspberryPi/assets/154501794/30ac086b-b7a3-4fcf-a1dd-cdda9182c13e)

# Write image to SD card
![292347253-572f4ea6-e9c2-4964-8acf-c21538225857](https://github.com/josthlee/RaspberryPi/assets/154501794/409b1f67-6a1a-4b4c-aefa-96eb084f74d0)

# pinout command

pi@raspberrypi:~ $ pinout

```
Description        : Raspberry Pi Zero W rev 1.1
Revision           : 9000c1
SoC                : BCM2835
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
---+ PiZero W    RUN o1   c|
 sd| V1.1 +---+   TV 1o   s|
---+      |SoC|           i|
| hdmi    +---+   usb pwr |
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

RUN:
RUN (1)
GND (2)

TV:
COMPOSITE (1)
      GND (2)

For further information, please refer to https://pinout.xyz/
```
