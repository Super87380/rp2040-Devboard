# RP2040 Devboard

This custom RP2040 Devboard features a built in 6 axis IMU, onboard LED, and 26 accessible GPIO Pins in a smaller package than a normal raspberry pi pico.

**Why did I make this?**\
I created this project to improve my PCB design skills, learn more about designing circuits around an MCU, and how to use an IMU. These skills I learnt will help me with my short term goal of making a device similar to a google home, and my long term goal of creating a thrust vector controlled rocket.


**What makes this devboard unique?**
- Built-in IMU which is not something ive seen
- It has a onboard LED that can be programmed to do anything you want (if that incudes turning on or off)
- Pretty compact package, I mean it is smaller than an official raspberry pi pico and has a built-in IMU

<img width="608" height="491" alt="image" src="https://github.com/user-attachments/assets/9a26d98f-7586-4c90-92d4-903828f62b20" />
<img width="423" height="946" alt="image" src="https://github.com/user-attachments/assets/8e23aeb8-efaa-45b7-bdac-1ae3d65ea4ed" />
<img width="1261" height="853" alt="image" src="https://github.com/user-attachments/assets/5aa40211-473a-48e5-9c8a-61ac945af4e3" />

**How to assemble**\
Assembling this PCB is pretty straightforward if you have experience soldering SMD components. Or you can just order it assembled through JLCPCBA or other similar services.
I recommend getting a stencil with your PCB's so that it's easier to apply the thermal paste. It's also very helpful to have a hotplate or soldering oven but it is possible to solder the components with just a soldering iron or a hot air gun.

**How to Flash**\
Flashing the MCU is super simple, simply hold down the boot button and plug the board into your computer. It then shows up as a USB drive in file explorer in which you can then drag in your firmware of choice like the simple onboard LED blinking provided.

**BOM**\
Prices in USD

| Part | Notes | Link | Quantity | Price Per Unit | Total |
| --- | --- | --- | --- | --- | --- |
| RP2040 | RP2040 MCU (only need 1, added 2 incase mistakes are made) | https://www.lcsc.com/product-detail/C2040.html | 2 | 0.9975 | 2.00 |
| W25Q16JVZPIQ | 16 Mbit (only need 1, added 2 incase mistakes are made) | https://www.lcsc.com/product-detail/C2456208.html | 2 | 1.92 | 3.84 |
| BMI323 | 6 Axis | https://www.lcsc.com/product-detail/C5368700.html | 1 | 3.26 | 3.26 |
| L327S120D11L | 12 Mhz | https://www.lcsc.com/product-detail/C5917263.html | 1 | 0.39 | 0.39 |
| TYPE-C16P3MDDGP073 | USB-C Receptacle | https://www.lcsc.com/product-detail/C2965608.html | 1 | 0.58 | 0.58 |
| P6E19A-602530-B1P | 19 Pin Male Headers, only need 2 (min 5) | https://www.lcsc.com/product-detail/C49451383.html | 5 | 0.0733 | 0.37 |
| 61300311121 | 3 Pin Male Headers, only need 1 (min 5) | https://www.lcsc.com/product-detail/C32713269.html | 5 | 0.0246 | 0.12 |
| CC0402KRX7R8BB104 | 0.1uf 0402 Capacitor, only need 13 (minimum 100) | https://www.lcsc.com/product-detail/C105883.html | 100 | 0.0073 | 0.73 |
| CGA0402X5R105K500GT | 1uf 0402 Capacitor, only need 2 (minimum 20) | https://www.lcsc.com/product-detail/C6119811.html | 20 | 0.0263 | 0.53 |
| TCC0603X5R106M350CT | 10uf 0603 Capacitor, only need 2 (minimum 10) | https://www.lcsc.com/product-detail/C22392391.html | 10 | 0.0542 | 0.54 |
| GJM1555C1H120GB01D | 12pf 0402 Capacitor, only need 2 (minimum 20) | https://www.lcsc.com/product-detail/C161305.html | 20 | 0.0306 | 0.61 |
| RC0402FR-075K1L | 5.1k 0402 Resistor, only need 2 (minimum 100) | https://www.lcsc.com/product-detail/C105872.html | 100 | 0.0025 | 0.25 |
| SR0402FR-7T10KL | 10k 0402 Resistor, only need 1 (minimum 20) | https://www.lcsc.com/product-detail/C854480.html | 20 | 0.024 | 0.48 |
| AC0402JR-074K7L | 4.7k 0402 Resistor, only need 2 (minimum 100) | https://www.lcsc.com/product-detail/C144709.html | 100 | 0.0023 | 0.23 |
| RC0402JR-071KL | 1k 0402 Resistor, only need 2 (minimum 100) | https://www.lcsc.com/product-detail/C105637.html | 100 | 0.0029 | 0.29 |
| RC0402FR-07270RL | 270 0402 Resistor, only need 1 (minimum 100) | https://www.lcsc.com/product-detail/C163474.html | 100 | 0.0019 | 0.19 |
| RCS040227R0FKED | 27 0402 Resistor, only need 2 (minimum 10) | https://www.lcsc.com/product-detail/C2100055.html | 10 | 0.0373 | 0.37 |
| CSL1104WBDW1 | 0603 White LED | https://www.lcsc.com/product-detail/C5603527.html | 1 | 0.311 | 0.31 |
| HX TS253015A2P 160gf | Boot Button, only need 1 (minimum 5) | https://www.lcsc.com/product-detail/C25168826.html | 5 | 0.1006 | 0.50 |
| PCB | Comes with 5 | | 1 | 2.1 | 2.10 |
| | | | | Sub Total: | 17.69 |
| | | | | Shipping: | 8.68 |
| | | | | Total: | 26.37 |

PCB Quote\
<img width="359" height="121" alt="image" src="https://github.com/user-attachments/assets/9a5c7661-a7e5-47cc-b566-7238e5facf0e" />

This project was made possible through the funding of Hackclub and Forge.\
More information on the build and design process can be found in my [Forge Project](https://forge.hackclub.com/projects/2720)
