# TWRP device tree for Lenovo Smart Tab M10 HD (TB-X505X)

## Release info
This is an unoffical build. Install at your own risk.


### About Device

![Lenovo Smart Tab M10 HD](https://static.lenovo.com/ww/campaigns/2019/smarttab/lenovo-smart-tab-gallery-5.jpg "Lenovo Smart Tab M10 HD (TB-X505F)")

Recovery Device Tree for Lenovo Smart Tab M10 HD TB-X505X
================================================================
Component   | Specs
-------:|:-------------------------
Chipset| Qualcomm Snapdragon 429 (SDM429)
CPU | ARM Cortex-A53, Quad-Core, 2.0 GHz
GPU     | Qualcomm Adreno 504, 650 MHz
Memory  | 2 GB (soldered)
Shipped Android Version | 8.0 (Oreo), upgrade to 9.0 (Pie)
Storage | 32 GB (eMPC)
MicroSD | Up to 256 GB
Battery | 4850 mAh, Li-Po (non-removable)
Display | 1280x800 pixels, 10.1"
Front Camera | 2.0 MP, fixed focus
Rear Camera  | 5.0 MP, auto focus
Wifi | dual band, 802.11a/ac/b/g/n
Bluetooth | v4.2
USB | micro USB


To build:

```
. build/envsetup.sh
lunch omni_X505X-eng
make clean
mka recoveryimage
```
