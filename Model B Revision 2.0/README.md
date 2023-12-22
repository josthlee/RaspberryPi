# PCB Print "Raspberry Pi (c)2011.12"

* Model B Revision 1.0 (ECN0001) (256MB)
* Model B Revision 2.0 (256MB)
* Model A Revision 2.0 (256MB)
* Model B Revision 2.0 (512MB)

# PCB Front Image
![RaspberryPIModelBRev2Front](https://github.com/josthlee/RaspberryPI/assets/154501794/cdd37b03-af58-4aae-993c-2a1f2b5a68dd)

# PCB Back Image
![RaspberryPIModelBRev2Back](https://github.com/josthlee/RaspberryPI/assets/154501794/a688b908-e623-4670-9179-ff38fbba911e)

# GPIO Pin Layout
![RaspberryPiModelBRev2GPIOLayout](https://github.com/josthlee/RaspberryPI/assets/154501794/f3f30c86-eeb9-4cce-bdad-4cfe0fd746b9)

# Raspberry Pi OS

## Download Raspberry Pi OS

https://www.raspberrypi.com/software/operating-systems/
![WeChat23f1519a76cd7af232947b3d23614e10](https://github.com/josthlee/RaspberryPI/assets/154501794/e52e9271-6f5e-4f2f-a8ad-b7cf02eb6cd1)

## Write image to SD card
![Screenshot 2023-12-22 at 08 58 56](https://github.com/josthlee/RaspberryPI/assets/154501794/572f4ea6-e9c2-4964-8acf-c21538225857)

# pinout command

root@raspberrypi:/home/pi# pinout 

```
Description        : Raspberry Pi B rev 2.0
Revision           : 000e
SoC                : BCM2835
RAM                : 512MB
Storage            : SD
USB ports          : 2 (of which 0 USB3)
Ethernet ports     : 1 (100Mbps max. speed)
Wi-fi              : False
Bluetooth          : False
Camera ports (CSI) : 1
Display ports (DSI): 1

+------------------| |--| |------+
| ooooooooooooo P1 |C|o |A|      |
| 1oooooooooooo    +-+oo+-+      |
|    1ooo             oo         |
| P5 oooo       +---+ oo        +====
|   |D          |SoC| oo        | USB
|   |S Pi Model +---+ oo        +====
|   |I B  V2.0        oo P3      |
|   |0             P2 11    +======
|                        C| |   Net
|            o           S| +======
=pwr      P6 1   |HDMI|  I|      |
+----------------|    |--0|------+

P1:
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

P2:
GPU JTAG (1)
GPU JTAG (2)
GPU JTAG (3)
GPU JTAG (4)
GPU JTAG (5)
GPU JTAG (6)
GPU JTAG (7)
GPU JTAG (8)

P3:
LAN JTAG (1)
LAN JTAG (2)
LAN JTAG (3)
LAN JTAG (4)
LAN JTAG (5)
LAN JTAG (6)
LAN JTAG (7)

P5:
    5V (1) (2) 3V3   
GPIO28 (3) (4) GPIO29
GPIO30 (5) (6) GPIO31
   GND (7) (8) GND   

P6:
RUN (1)
GND (2)

For further information, please refer to https://pinout.xyz/
```
