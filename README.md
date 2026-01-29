# TOC
At the beginning I was planning to put here only official firmwares found somewhere in update files and internet but now, with help from people involved in process of reverse enginnering of uvk5 you can find here some knowledge and findings regarding our very wallet friendly yet so capable radio. Here is table of contents of this repository.

## Build your own firmware - [/uvmod_kitchen](/uvmod_kitchen)
You can select what you want to include in your modded firmware. If you want unlock all frequencies but also have custom frequency steps? This is section for you. Thanks to this tool you can mix and match different mods to be included in final firmware. All mods are basing on firmware version k5_2.01.26.

## Build your own firmware - [/uvmod_kitchen_31](/uvmod_kitchen_31)
Same as above but all mods are basing on firmware version k5_2.01.31.

## Documents - [/docs](/docs)
Some (incomplete) documents with info about CPU I/O pins, memory mappings, firmware format etc. 

## Font and graphics - [/font_and_graphics](/font_and_graphics)
Simple python script which extracts from firmware all bitmaps used in radio's user interface. It works as substitute of documentation.

## Datasheets and drawings - [/hardware](/hardware)
Here are all the efforts of searching internet for datasheets but also drawings of reverse engineered schematics and high resolution photos of PCB.

## OpenOCD configs - [/openocd](/openocd)
Tools necessary to unbrick your radio or dump flash memory.

## Utility scripts - [/python-utils](/python-utils)
Python library and sample scripts which leverage official communication protocol. You can dump EEPROM and reboot your radio or decode firmware. 

## Quansheng UV-K5 Firmware collection - [/firmware](/firmware)
Only stock firmwares, no mods, no alterations. If you want modified firmware ready to flash please check out [Andrej](https://github.com/Tunas1337/UV-K5-Modded-Firmwares)'s repo

| Firmware_Version                                  | Programming software                                                       | Firmware-Updater |
| --                                                | --                                                                         | --               |
| [k5_2.01.17](firmware/k5_v2.01.17_publish.bin)    |                                                                            |                  |
| [k5_2.01.19](firmware/k5_v2.01.19_publish.bin)    |                                                                            | 1.1.11           |
| [k5_2.01.23](firmware/k5_v2.01.23_publish.bin)    | V1.0.38 2023-02-11 07:49:36                                                | 1.1.11           |
| [k5_2.01.25](firmware/k5_v2.01.25_publish.bin)    | Not released, dumped from device                                           | n/a              |
| [k5_2.01.26](firmware/k5_v2.01.26_publish.bin)    | V1.0.38                                                                    | 1.1.12           |
| [k5_2.01.27](firmware/k5_v2.01.27_flashable.bin)  | Not released, dumped from device by @CloverGit                             | n/a              |
| [k5_2.01.27](firmware/RT590_v2.01.27_publish.bin) | Released on [Radtel Site](https://www.radtels.com/pages/software-download) | 1.1.12           |
| [k5_2.01.31](firmware/k5_v2.01.31_publish.bin)    | Official fw, released 2023-09-02 (**UV-K5**)                               | 1.1.12           |
| [k5_2.01.32](firmware/RT590_v2.01.32_publish.bin) | Released on [Radtel Site](https://www.radtels.com/pages/software-download) | 1.1.12           |
| [k5_2.01.33](firmware/k5_v2.01.33_publish.bin)    | Official fw, released 2024-03-05 (**UV-K5**)                               | 1.1.12           |
| [k5_2.01.35](firmware/K5_ms_lpf32_v2.01.35_publish.bin)    | Official fw, released 2024-07 (**UV-K5**)                         | n/a              |
| [k5_2.01.35](firmware/k5_v2.01.35_publish.bin)    | Official fw, released 2024-11-09 (**UV-K5**)                               | n/a              |
| [k5_2.01.36](firmware/k5_v2.01.36_publish.bin)    | Official fw, released 2025-03-20 (**UV-K5**)                               | n/a              |
| [k5_2.01.39](firmware/k5_v2.01.39_publish (2025-09-02).bin)    | Official fw, , released 2025-09-02                            | n/a              |
| [k5_2.01.39](firmware/k5_v2.01.39_publish.bin)    | Not released, dumped from device 2025-07-19 (**universal**) #143           | n/a              |
| [k6_3.00.10](firmware/k6_v3.00.10_flashable.bin)  | Not released, dumped from device (**UV-K6**)                               | n/a              |
| [k6_3.00.15](firmware/k6_v3.00.15_publish.bin)    | Official fw, released 2023-09-02 (**UV-K6**)                               | 1.1.12           |
| [k6_3.00.17](firmware/k6_v3.00.17_publish.bin)    | Official fw, released 2024-03-05 (**UV-K6**)                               | 1.1.12           |
| [k6_3.00.18](firmware/K6_ms_lpf32_v3.00.18_publish.bin)    | Official fw, released 2024-07 (**UV-K6**)                         | n/a              |
| [k6_3.00.18](firmware/k6_v3.00.18_publish.bin)    | Official fw, released 2024.11.09                                           | n/a              |
| [k6_3.00.19](firmware/k6_v3.00.19_publish.bin)    | Official fw, released 2024-03-20 (**UV-K6**)                               | n/a              |
| [k6_3.00.22](firmware/K6_v3.00.22_publish (2025-09-02).bin)    | Official fw, released  2025.09.02                             | n/a              |
| [k6_3.00.22](firmware/k6_v3.00.22_publish.bin)    | Not released, dump by @xufan6 2025-08-04 (**universal**) #144              | n/a              |
| [k5_4.00.01](firmware/k5_v4.00.01_flashable.bin)  | Not released, dumped from device (**UV-5R PLUS**)                          | n/a              |
| [k5_4.00.09](firmware/k5_v4.00.09_publish)        | Official fw, released  2025.09.02                                          | n/a              |
| [k5_4.00.06](firmware/RT600_v4.00.06_publish.bin) | Released on [Radtel Site](https://www.radtels.com/pages/software-download) | 1.1.12           |
| [k5_4.00.07](firmware/k5_v4.00.07_publish.bin)    | From @Andy-GM (see #117) (**UV-5R PLUS**)                                  | n/a              |
| [k5_7.01.09](firmware/K5CHI-071 V.7.01.09.bin)    | From @Andy-GM (see #117) (**UV-5R PLUS**)                                  | n/a              |
| [k5_7.00.11](firmware/K5ENG-071_v7.00.11_publish.bin)    | From @Andy-GM (see #117) (**UV-5R PLUS**)                                  | n/a              |
| [k5_py030_v1.01.07](firmware/k5_py030_v1.01.07.bin)           | UV-K5 V2 Firmware v1.01.07 2025.12.04                                          | n/a              |
| [k5_py030_v1.01.07](firmware/k5_py030_v1.02.01_publish.bin)   | UV-K5 V2 Firmware v1.02.01 2025.12.04                                          | n/a              |


All files from table are already encoded and can be directly flashed using firmware updater V1.1.12. 


# Links
* ![New_Logo](https://github.com/amnemonic/Quansheng_UV-K5_Firmware/assets/29899901/9b6b8303-6a95-4c9f-81b7-52782500f833) [Multi-functional K5/6 Firmware](https://github.com/losehu/uv-k5-firmware-custom/blob/main/README_en.md) by [@losehu](https://github.com/losehu)
*  [A merge between **OneOfEleven/uv-k5-firmware-custom** and **fagci/uv-k5-firmware-fagci-mod**](https://github.com/egzumer/uv-k5-firmware-custom) by [@egzumer](https://github.com/egzumer)
* [Custom open source firmware](https://github.com/OneOfEleven/uv-k5-firmware-custom) by [@OneOfEleven](https://github.com/OneOfEleven)
* [On-line firmware modder](https://whosmatt.github.io/uvmod/)  by [@whosmatt](https://github.com/whosmatt)
* [Quansheng UV-K5 Wiki](https://github.com/ludwich66/Quansheng_UV-K5_Wiki/wiki) by [@ludwich66](https://github.com/ludwich66)
* [UV-K5-Modded-Firmwares](https://github.com/Tunas1337/UV-K5-Modded-Firmwares) by [@Tunas1337](https://github.com/Tunas1337) (repo archived on Feb 16, 2024)
* [uvk5-reverse-engineering](https://github.com/sq5bpf/uvk5-reverse-engineering) | [CHIRP Driver](https://github.com/sq5bpf/uvk5-reverse-engineering/blob/main/uvk5.py) | [Official CHIRP Driver](https://github.com/kk7ds/chirp/blob/master/chirp/drivers/uvk5.py) by [@sq5bpf](https://github.com/sq5bpf)
* [qs-uvk5-firmware-modder](https://github.com/fagci/qs-uvk5-firmware-modder) by [@fagci](https://github.com/fagci)
* [UV_K5_playground](https://github.com/piotr022/UV_K5_playground) by [@piotr022](https://github.com/piotr022)
* [UV_K5-Tools](https://github.com/manujedi/UV_K5-Tools) by [@manujedi](https://github.com/manujedi)
* [Quansheng-UV-K5](https://github.com/dkxce/Quansheng-UV-K5) by [@dkxce](https://github.com/dkxce)
* [Hackaday article 🛠](https://hackaday.com/2023/06/23/easy-modifications-for-inexpensive-radios/)
* [Telegram Channel - Global](https://t.me/quansheng_uvk5_en)
* [Telegram Channel - 🇧🇬 BG](https://t.me/quansheng_uvk5_bg)
* [Telegram Channel - 🇹🇷 TR](https://t.me/quansheng_uvk5_tr)
* [Telegram Channel - 🇷🇺 RU](https://t.me/uv_k5)
* [Telegram Channel - 🇪🇸 ES -> First one](https://t.me/Quansenguvk5) 
* [Telegram Channel - 🇪🇸 ES -> Second channel](https://t.me/QuanShengES)
* [Telegram Channel - 🇮🇹 IT](https://t.me/+W31XPFpurWk0NzM0)
* [Telegram Channel - 🇵🇱 PL](https://t.me/uvk5_pl)
* [Telegram Channel - 🇩🇪 DE](https://t.me/quanshenguv5kde)
* [Telegram Channel - 🇺🇦 UA](https://t.me/radioamators/38782)
* [Telegram Channel - 🇫🇮 FI](https://t.me/UVK5_Suomi)
* Official UV-K5 support page:              [Chinese](http://qsfj.com/support/downloads/3002) | [English](http://en.qsfj.com/support/downloads/3002)
* Official UV-K5 product page:              [Chinese](http://qsfj.com/products/3002)          | [English](http://en.qsfj.com/products/3002)
* Official UV-K5(8) aka UV-K6 support page: [Chinese](http://qsfj.com/support/downloads/3268) | [English](http://en.qsfj.com/support/downloads/3268)
* Official UV-K5(8) aka UV-K6 product page: [Chinese](http://qsfj.com/products/3268)          | [English](http://en.qsfj.com/products/3268)
* [FCC Reports](https://fcc.id/XBPUV-K5) / [fcc.gov](https://apps.fcc.gov/oetcf/eas/reports/ViewExhibitReport.cfm?mode=Exhibits&RequestTimeout=500&calledFromFrame=Y&application_id=8sqkxgC%2F1cYNHF0lGkSAwA%3D%3D&fcc_id=XBPUV-K5)
* [DP32G030 Product page](https://dnsj88.com/dp32g030lq32)
* [DP32G030 Datasheet](https://dnsj88.com/filedownload/493463)
* [Google Drive folder with useful info](https://drive.google.com/drive/folders/1NmcPb5yl5jnz7uWBO-c4B89XYL5AZeHw)
* Facebook - [Quansheng Electronics Co., Ltd.](https://www.facebook.com/QuanshengRadios/)
* Facebook - [Quansheng UV-K5 User's Group](https://www.facebook.com/groups/229333669483573/)
* Facebook - [QuanSheng UV-K5 UV-K5(8) UV-K6 - Polska](https://www.facebook.com/groups/205485455659292/)
* Facebook - [Quansheng UV-K5 UK Users](https://www.facebook.com/groups/2291286734508728/)
* Facebook - [Quansheng UV-K5 Philippines User Group](https://www.facebook.com/groups/678587170703812/)


### Thanks for all contributors

<a href="https://github.com/amnemonic/Quansheng_UV-K5_Firmware/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=amnemonic/Quansheng_UV-K5_Firmware" />
</a>
