# TWRP Device Tree For TECNO Spark 3 Pro

## About Device

![TECNO Spark 3 Pro](https://fdn2.gsmarena.com/vv/pics/tecno-mobile/tecno-pouvoir-3-pro-2.jpg)

### Specifications

Component Type | Details
-------:|:-------------------------
CPU     | Octa-core 2.0 GHz Cortex-A53 Helio P22
Platform | MediaTek MT6761
GPU     | PowerVR GE8320
Architecture | 64 bit
Memory  | 2 GB RAM
Shipped Android Version | 	Android 9.0 Pie, HIOS 5.0
Storage | 32 GB F2FS (expandable storage up to 256GB (VFAT))
Battery | 3500 mAh
Height | 154.3 mm
Width | 75.5 mm
Thickness | 7.9 mm
Weight | -
Display | 6.2" (96.7 cm2)
Screen resolution | 720 x 1500 pixels
Pixel density | 268 PPI
Video | 1080p, 720p video, 30fps
Primary Camera | 13 MP + 2 MP Dual Rear Camera, PDAF
Secondary Camera | 8 MP, f/2.0, 1.6µm
Quick charging | No
Wifi | Yes, IEEE802.11 a/b/g/n, Supports 5G Wi-Fi Signal / Wi-Fi Direct / Wi-Fi Display
Bluetooth | v5.0, Bluetooth HID, A2DP, LE
Micro USB | Yes
NFC | No
Network support | Both SIM slots are compatible with 4G, support 4G VoLTE in both slots simultaneously
GPRS | Available
EDGE | Available
SIM size | SIM1: Nano, SIM2: Nano
CARD slot |	microSD, up to 128 GB (dedicated slot)
Sensors | Fingerprint (rear-mounted), Accelerometer, Gyroscope, Geomagnetic Sensor

Network | Bands
-------:|:-------------------------
2G | GSM 850 / 900 / 1800 / 1900 - SIM 1 & SIM 2
3G | HSDPA 850 / 900 / 2100
4G | LTE band 1(2100), 3(1800), 5(850), 8(900), 38(2600), 40(2300), 41(2500)
Speed | HSPA 42.2/5.76 Mbps, LTE Cat4 150/50 Mbps

**This device tree can be used to build TWRP for TECNO Spark 3 Pro**


## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_KB8-eng
mka recoveryimage
```
