# T-Rex

A 5x12 Ortholinear QMK compatible Keyboard. The keyboard is designed to be easily ordered by anyone from a PCB manufacturer and assembled by yourself. The case is 3D printable and can be assembled with easily available parts. The Firmware is currently only on my fork of [qmk](https://github.com/SylivanKenobi/qmk_firmware/tree/master/keyboards/t_rex). The keyboard is compatible with Pro Micro controllers and their derivatives. Additionally, it supports WS2812 LED strips as an extra feature.

Example parts:
* [Controller](https://splitkb.com/products/pro-micro-atmega32u4-5v-16mhz)
* [Diodes](https://splitkb.com/products/tht-diodes)
* [Reset button](https://mechboards.co.uk/products/reset-switches?variant=40823623090381)
* 60 Switches
* 60 Keycaps
* 6x [M2x8 Standoffs](https://splitkb.com/products/brass-m2-spacers?variant=42396969173251)
* 3D printed case([stl file](cases/minimal-case.stl))
* 6x M2x10 screws, 6x M2x5 screws

## Assembly

### PCB

1. Solder diodes on top of board, orientation is marked by silkscreen
1. Clip diode leftovers
1. Solder controller headers and reset button
1. Solder switches
1. Solder controller
1. [Flash firmware](https://github.com/SylivanKenobi/qmk_firmware/tree/master/keyboards/t_rex)

> If you socket your controller, mount the controller before the switches and test the PCB.

### Cases

#### Minimal Case

1. Print [case](cases/minimal-case.stl) with 3d printer
1. Mount standoffs with M2x5 from the top
1. Mount case with M2x10 to standoffs

#### Closed Case

1. Print both sides of the [case](cases/closed-falt-case) with 3d printer
1. Insert M2x4x3.5 Heat set inserts([exapmle](https://www.bastelgarage.ch/gewindeeinsatze-messing-insert-set-360-stuck))
1. Mount pcb to case with M2x5 screws

## Plate

I would recommend using PCB-Mounted switches for this board. There is a 3d printable plate for the t-rex in this repo([file](cases/plate.stl)). The plate works but because it's 3d printed it's not that great.

## Roadmap

1. Merge firmware to QMK

![image of keyboard](assets/t-rex-top.jpg)
![image of keyboard backside](assets/t-rex-back.JPG)