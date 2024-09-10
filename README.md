
# Muikku42

Muikku42 is a RP2040 Zero based 42-key column staggered split keyboard. The main goal is to make a affordable split keyboard, no need for SMD components or 3D printed parts. Design is inpired from REVIUNG41 and Corne keyboards.

PCB is designed for MX style 5-pin switches. PCB is reversible and same PCB design can be used as bottom plate.

![](https://raw.githubusercontent.com/Squalius-cephalus/muikku42/main/muikku42_render.png)

***PCB design has not been tested. This is more of a concept than a real product. Current gerber-files should work just fine, but I still recommend checking for errors.***

QMK firmware is in the works.

## BOM - Bill of materials
|Part | Quantity |
|--|--|
| 5-pin MX compatible keyswitch | 42 |
| MX compatible 1u keycap | 42 |
| Diodes 1N4148 | 42 |
| Brass standoff M2 4mm | 16 |
| M2 Flat head bolt 3mm | 16 |
| 2mm rubber feet | 16 |
| PCB | 4 |
| RP2040-Zero | 2 |
| PJ320A Audio Socket | 2 |
| TRRS cable | 1 |
| USB-C cable | 1 |

Many PCB manufacturers have a minium order quantity of 5 pcs.
## More info
![](https://raw.githubusercontent.com/Squalius-cephalus/muikku42/main/info.png)
### TODO
1. Create firmware
2. Build guide

----
PCB design uses footprints from [ScottoKeebs](https://github.com/joe-scotto/scottokeebs/tree/main/Extras/ScottoKicad "ScottoKeebs"), [keyswitches.pretty](https://github.com/daprice/keyswitches.pretty "keyswitches.pretty")  and [kbd library.](https://github.com/foostan/kbd "kbd library.")
