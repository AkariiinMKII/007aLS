# 007_a_L(onely)_S(pace)

A custom keyboard based on STM32F103 and QMK, with only a space bar, but expandable.

![pic](./.doc/20240423_223940.JPG)
![pic](./.doc/20240423_223957.JPG)
![pic](./.doc/20240423_224233.JPG)
![pic](./.doc/20240423_224732.JPG)
![pic](./.doc/20240423_224151.JPG)
![pic](./.doc/20240423_224107.JPG)

## Hardware

### PCB

See files in [PCB](./PCB).

[EasyEDA Pro](https://pro.easyeda.com/editor) is needed to edit `.epro` file.

### 3D printed Case

See files in [Case](./Case).

### Parts to purchase (in Chinese only)

_All of these should be available in China Mainland._

|内容|数量|备注|链接|
|-|:-:|-|-|
|M2\*17mm 六角铜柱|4|外壳固定用|<https://detail.tmall.com/item.htm?id=644381840317>|
|M2\*7mm 扁头螺丝 头部直径6mm|8|外壳固定用，一端拧上后卡入上盖|<https://detail.tmall.com/item.htm?id=718532926918>|
|M2\*3mm 扁头螺丝|4|定位板固定用|<https://detail.tmall.com/item.htm?id=13836098491>|
|M2\*3.5mm 六角铜柱|2|定位板固定用|<https://item.taobao.com/item.htm?id=743158489039>|
|M2绝缘垫片 直径4mm 厚0.5mm|2|定位板固定用，用于PCB下方|<https://detail.tmall.com/item.htm?id=535558533487>|
|M2对锁螺丝 母钉螺杆4mm 外直径3mm|2|小板固定用 [\*1]，母钉用于小板上方|<https://detail.tmall.com/item.htm?id=616768747669>|
|M3绝缘垫片 直径6mm 厚0.5mm|2|小板固定用，用于小板上方|<https://detail.tmall.com/item.htm?id=535558533487>|
|13x4x2.5mm 圆头脚垫|4||<https://item.taobao.com/item.htm?id=579251575258>|
|FPC排线 4pin 间隔0.5mm 长度70mm 同向|1||<https://item.taobao.com/item.htm?id=616354301362>|

*1: 如对外观有要求可购买外壳螺丝同款的 M2\*3 扁头螺丝代替原有螺丝

## Firmware

See files in [Firmware](./Firmware).

### Bootloader

[STM32duino](https://github.com/rogerclarkmelbourne/STM32duino-bootloader/blob/master/bootloader_only_binaries/generic-none_bootloader.bin)

### QMK

Added in this [commit](https://github.com/AkariiinMKII/qmk_firmware/commit/17e1cea3b4afec91959c45b3cf8241e8540ba4bb).
