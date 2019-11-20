Device Tree for Redmi Note 8 Pro (begonia)
==========================================

The Redmi Note 8 Pro (codenamed _"begonia"_) is a high-end, mid-range smartphone from Xiaomi.
It was released in September 2019.

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core                                                                                                                      |
| Chipset                 | Mediatek Helio G90T                                                                                                            |
| GPU                     | Mali-G76 MC4                                                                                                                   |
| Memory                  | 6/8 GB RAM                                                                                                                     |
| Shipped Android Version | 9.0                                                                                                                            |
| Storage                 | 64/128/256 GB                                                                                                                  |
| Battery                 | Non-removable Li-Po 4500 mAh battery                                                                                           |
| Display                 | 1080 x 2340 pixels, 19.5:9 ratio (~395 ppi density)                                                                            |
| Camera (Back)(Main)     | 64 MP, f/1.9, 26mm (wide), 1/1.7", 0.8µm, PDAF                                                                                |
| Camera (Front)          | 20 MP, f/2.0, 0.9µm                                                                                                           |

## Device picture
![begonia](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-redmi-note-8-pro-01.jpg)

## Build instructions

```
# Compiling
$ export ALLOW_MISSING_DEPENDENCIES=true
$ . build/envsetup.sh
$ lunch omni_begonia-eng
$ make -jx recoveryimage //replace x in -jx with number of cores you want to allot for compilation

```
**Copyright 2019 The Android Open Source Project**
