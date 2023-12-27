# RGB LED Adventures
This is starting with my 8x8 WS2812B project as shown on my channel [https://youtu.be/@PlatimaTinkers](https://youtube.com/@PlatimaTinkers)

I started this as I think all the current options are pretty crap designs, or overpriced.

* PCBWay Project: https://www.pcbway.com/project/shareproject/8x8_WS2812B_RGB_LED_Board_w_Mounts_MCU_SOC_Positions_46045ab1.html
* Hackster Project: https://www.hackster.io/platimatinkers/8x8-ws2182b-led-array-w-mcu-soc-support-mounts-b02998

## Goals
1. Easy to physically mount
2. Easy to chain
3. Make use of modern power/comms like USB-C
4. Cost effective aka no massive markup
5. Supports multiple SOCs/MCUs
6. Overcome FPS issues with big arrays via onboard controllers
7. Self-documenting with silkscreen
8. Open-source
9. Fun

## Notes
### 2023-12-21
* USB-C is only for chaining DIN/DOUT and power
* There is a 0-ohm resistor to isolate the DIN for the sake of adding multiple controllers.
* The mounts are 2mm, spaced 8mm in, 16mm across, and two per side so it can be physically stable in any configuration.

## YouTube Videos About This Project
 - [Part 1 - First Prototype & Test](https://youtu.be/V4Wd6AvVf8U) ([Reddit](https://www.reddit.com/r/Platima/comments/18opq3h/i_was_annoyed_at_how_crap_all_rgb_matrixes/)) ([Blog](https://plati.ma/other-neopixel-matrixes-are-crap/))
 - [Part 2 - TBC]()

## Updates
* **2023-12-21**: Initial commit of 8x8 WS2812B Project

## Shop
Buy spare boards, modules, and similar from me: https://shop.plati.ma/

## Simulator
Using: https://jasoncoon.github.io/led-mapper/
Layout:
```
0	15	16	31	32	47	48	63
1	14	17	30	33	46	49	62
2	13	18	29	34	45	50	61
3	12	19	28	35	44	51	60
4	11	20	27	36	43	52	59
5	10	21	26	37	42	53	58
6	9	22	25	38	41	54	57
7	8	23	24	39	40	55	56
```
