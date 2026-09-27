# RP2040 Devboard

This custom RP2040 Devboard features a built in 6 axis IMU, onboard LED, and 26 accessible GPIO Pins in a smaller package than a normal raspberry pi pico.

**Why did I make this?**\
I created this project to improve my PCB design skills, learn more about designing circuits around an MCU, and how to use an IMU. These skills I learnt will help me with my short term goal of making a device similar to a google home, and my long term goal of creating a thrust vector controlled rocket.


**What makes this devboard unique?**
- Built-in IMU which is not something ive even seen
- It has a onboard LED that can be programmed to do anything you want (if that incudes turning on or off)
- Pretty compact package, I mean it is smaller than an official raspberry pi pico and has a built-in IMU

<img width="608" height="491" alt="image" src="https://github.com/user-attachments/assets/9a26d98f-7586-4c90-92d4-903828f62b20" />
<img width="423" height="946" alt="image" src="https://github.com/user-attachments/assets/8e23aeb8-efaa-45b7-bdac-1ae3d65ea4ed" />
<img width="1261" height="853" alt="image" src="https://github.com/user-attachments/assets/5aa40211-473a-48e5-9c8a-61ac945af4e3" />

**How to assemble**
Assembling this PCB is pretty straightforward if you have experience soldering SMD components. Or you can just order it assembled through JLCPCBA or other similar services.
I recommend getting a stencil with your PCB's so that it's easier to apply the thermal paste. It's also very helpful to have a hotplate or soldering oven but it is possible to solder the components with just a soldering iron or a hot air gun.

**How to Flash**
Flashing the MCU is super simple, simply hold down the boot button and plug the board into your computer. It then shows up as a USB drive in file explorer in which you can then drag in your firmware of choice.

**BOM**

| Part | Notes | Link | Quantity | Price Per Unit | Total |
| --- | --- | --- | --- | --- | --- |
| SC0914(13) | RP2040 MCU | https://www.digikey.ca/short/q2dff4nt | 1 | 1.19 | 1.19 |
| W25Q16JVZPIQ TR | 16 Mbit | https://www.digikey.ca/short/8r94jqwh | 1 | 3.14 | 3.14 |
| BMI323 | 6 Axis | https://www.digikey.ca/short/2492bw8v | 1 | 6.11 | 6.11 |
| 830108206909 | 12 Mhz | https://www.digikey.ca/short/fd9mfhqf | 1 | 0.78 | 0.78 |
| USB4105-GF-A-120 | USB-C Receptacle | https://www.digikey.ca/short/v23r8qfb | 1 | 1.17 | 1.17 |
| PH1-19-UA | 19 Pin Male Headers | https://www.digikey.ca/short/fh214w20 | 2 | 0.37 | 0.74 |
| 61300311121 | 3 Pin Male Headers | https://www.digikey.ca/short/1tz5pv83 | 1 | 0.19 | 0.19
| C0402C104K4RAC7411 | 0.1uf 0402 Capacitor | https://www.digikey.ca/short/5cj4qq82 | 13 | 0.138 | 1.794 |
| GRT155R61E105KE01D | 1uf 0402 Capacitor | https://www.digikey.ca/short/b3qwttt7 | 2 | 0.19 | 0.38 |
| CL10A106MA8NRNC | 10uf 0603 Capacitor | https://www.digikey.ca/short/28rz0qvv | 2 | 0.47 | 0.94 |
| C0402C120J5GACTU | 12pf 0402 Capacitor | https://www.digikey.ca/short/4mzbf5rd | 2 | 0.19 | 0.38 |
| RC0402JR-075K1L | 5.1k 0402 Resistor | https://www.digikey.ca/short/2ww07hnm | 2 | 0.16 | 0.32 |
| RC0402JR-1310KL | 10k 0402 Resistor | https://www.digikey.ca/short/npzj902q | 1 | 0.16 | 0.16 |
| RC0402JR-074K7P | 4.7k 0402 Resistor | https://www.digikey.ca/short/83b82rmh | 2 | 0.16 | 0.32 |
| RC0402JR-071KP | 1k 0402 Resistor | https://www.digikey.ca/short/cvvqjf70 | 2 | 0.16 | 0.32 |
| RC0402FR-07270RL | 270 0402 Resistor | https://www.digikey.ca/short/9w7j8rzp | 1 | 0.16 | 0.16 |
| CRG0402F27R | 27 0402 Resistor | https://www.digikey.ca/short/2hpmh15d | 2 | 0.16 | 0.32 |
| LTST-T180UWET | 0603 White LED | https://www.digikey.ca/short/f3bf70m5 | 1 | 0.39 | 0.39 |
| B3U-1000P | Boot Button | https://www.digikey.ca/short/qbbj23fh | 1 | 1.83 | 1.83 |
| PCB | Comes with 5 | | 1 | 2.1 | 2.1 |
| | | | | Sub Total: | 22.73 |

This project was made possible through the funding of Hackclub and Forge.
