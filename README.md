
# Muikku42

Muikku42 is a Raspberry Pi Pico based 42-key column staggered split keyboard. The main goal is to make a affordable DIY split keyboard and keep the design simple. Easy of building is one of the main goal. Design is inpired from REVIUNG41 and Corne keyboards.

PCB is designed for MX style 5-pin switches, but with optional plate 3-pin switches can be used. PCB is reversible and same PCB design can be used as bottom plate.

![](https://github.com/Squalius-cephalus/muikku42/blob/main/muikku42_render.png)

***PCB design has not been tested. This is more of a concept than a real product. Current gerber-files should work just fine, but I still recommend checking for errors.***

QMK firmware is in the works.

## BOM - Bill of materials
|Part | Quantity |
|--|--|
| 5-pin MX compatible keyswitch | 42 |
| Kailh MX compatible hotswap socket | 42 |
| MX compatible 1u keycap | 42 |
| 2mm rubber feet | 16 |
| PCB | 2 |
| Raspberry Pi Pico | 2 |
| PJ320A Audio Socket | 2 |
| TRRS cable | 1 |
| USB-C cable | 1 |

If you are using 3-pin switches, 3D printed plate is required.


### TODO
1. Create firmware
2. Build guide

----
PCB design uses footprints from [ScottoKeebs](https://github.com/joe-scotto/scottokeebs/tree/main/Extras/ScottoKicad "ScottoKeebs"), [keyswitches.pretty](https://github.com/daprice/keyswitches.pretty "keyswitches.pretty")  and [kbd library.](https://github.com/foostan/kbd "kbd library.")
