# Raspberry Pi Model Identification

#### uname -a

```
pi@raspberrypi:~ $ uname -a
Linux raspberrypi 6.1.0-rpi7-rpi-v6 #1 Raspbian 1:6.1.63-1+rpt1 (2023-11-24) armv6l GNU/Linux
```

#### getconf LONG_BIT

```
pi@raspberrypi:~ $ getconf LONG_BIT
32
```

#### /usr/bin/pinout

```
root@raspberrypi:/home/pi# pinout 
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

#### cat /proc/cpuinfo

```
processor	: 0
model name	: ARMv6-compatible processor rev 7 (v6l)
BogoMIPS	: 697.95
Features	: half thumb fastmult vfp edsp java tls 
CPU implementer	: 0x41
CPU architecture: 7
CPU variant	: 0x0
CPU part	: 0xb76
CPU revision	: 7

Hardware	: BCM2835
Revision	: 000e
Serial		: 00000000fd6a36fb
Model		: Raspberry Pi Model B Rev 2
```

#### cat /proc/device-tree/model

```
Raspberry Pi Model B Rev 2
```

# Raspberry Pi First Time Configuration

#### raspi-config
