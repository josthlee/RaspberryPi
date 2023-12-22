# PCB Print "Raspberry Pi 3 Model B+"

* Raspberry Pi 2017

  
# PCB Front Image
![24491703210011_ pic](https://github.com/josthlee/RaspberryPi/assets/154501794/23eb04b2-7adc-4dc4-afde-67dee57959b3)

# PCB Back Image
![24501703210012_ pic](https://github.com/josthlee/RaspberryPi/assets/154501794/1e27949e-ac86-4e5f-a654-2afd30fb143a)

# GPIO Pin Layout
![GPIO-Pinout-Diagram-2](https://github.com/josthlee/RaspberryPi/assets/154501794/fd8dbf9b-531e-4d27-b869-e5b9e25bf5f0)
![pi3_5F00_gpio](https://github.com/josthlee/RaspberryPi/assets/154501794/bfdf7e4a-9877-494a-81d8-376a88019a92)

# Raspberry Pi OS

## Download Raspberry Pi OS

https://www.raspberrypi.com/software/operating-systems/
![24511703212678_ pic](https://github.com/josthlee/RaspberryPi/assets/154501794/63d6aaa9-2a5f-42d1-9a30-90124a6ac664)

## Write image to SD card
![Screenshot 2023-12-22 at 10 39 03](https://github.com/josthlee/RaspberryPi/assets/154501794/3aeb4dfc-cf77-4b08-b9aa-d8978025c0aa)

# pinout command

root@raspberrypi:/home/pi# pinout

```
Description        : Raspberry Pi 3B+ rev 1.3
Revision           : a020d3
SoC                : BCM2837
RAM                : 1GB
Storage            : MicroSD
USB ports          : 4 (of which 0 USB3)
Ethernet ports     : 1 (300Mbps max. speed)
Wi-fi              : True
Bluetooth          : True
Camera ports (CSI) : 1
Display ports (DSI): 1

,--------------------------------.
| oooooooooooooooooooo J8 PoE +====
| 1ooooooooooooooooooo   12   | USB
|  Wi                    oo   +====
|  Fi  Pi Model 3B+ V1.3         |
| |D     ,---.           1o   +====
| |S     |SoC|            RUN | USB
| |I     `---'                +====
| |0               C|            |
|                  S|       +======
|                  I| |A|   |   Net
| pwr      |HDMI|  0| |u|   +======
`-| |------|    |-----|x|--------'

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
POWER ENABLE (1)
         RUN (2)

POE:
TR01 TAP (1) (2) TR00 TAP
TR03 TAP (3) (4) TR02 TAP```
