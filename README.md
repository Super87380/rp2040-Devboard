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
