<h1 align="center">
  <br>
  <img width=19% alt="logo perdican" src="https://github.com/user-attachments/assets/61a4c824-8660-4d4c-9045-3ede98157f96" />
  <br>
  APX RC PLANE V2
  <br>
</h1>

<h4 align="center">
The V2 of my RC plane, but this one is 3D printed!
</h4>

<div align="center">

![License](https://img.shields.io/badge/License-Unlicense-blue.svg)
![Project](https://img.shields.io/badge/Project-Hardware-yellow.svg)
![Series](https://img.shields.io/badge/Series-APX-red.svg)

</div>

<p align="center">
  <a href="#about-the-project">About</a> •
  <a href="#repository-structure">Structure</a> •
  <a href="#schematic-on-kicad">Schematic</a> •
  <a href="#pcb-on-kicad">Images</a> •
  <a href="#bill-of-materials">BOM</a> •
  <a href="#license">License</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#credits">Credits</a>
</p>

<br>
<br>
<p align=center>
<img width=70% alt="image" src="https://github.com/user-attachments/assets/2972ea26-00a6-4626-b22f-64dd901bf482" />

</p>

## About the Project

**APX RC PLANE** is a simple and cost effective RC PLANE that has 3 axis and is 3D printed with lightweight filament.

### Features

- **STM32G431CBT6** MCU 32-Bit 170MHz 128KB (128K x 8) FLASH 48-LQFP (7x7)
- **LSM6DS3TR-C** 6 axis IMU with Accelerometer, Gyroscope, Temperature
- **14 GPIO pins** to help make any hardware project
- **4 debugging pins** with SWCLK, SWDIO, GND and 3V3
- **Status LEDs** to see any error from 5V or 3V3
- **GPIO linked LED** to program it without needing an external LED
- **GPIO linked button** to use it without needing an external button
- **BOOT and RESET buttons**
- **USB-C input**
- **pixelated silkscreen art** to improve the overall look
- **Small size** of 3.7*3.9 cm

## Repository Structure

- `schematic/` - wiring diagram of the electronics
- `CAD/` — full 3d model
- `images/` — images used in the README and documentation

## Schematic on KiCad

Source : `schematic/`  

<img width=100% alt="schematic rc plane" src="httpachments/assets/c4f7ff39-6ec6-476f-b53c-51222a88055d" />


## Images

Source : `images/`  

<div align="center">
  <table>
    <tr>
      <td valign="bottom"><img width=100% alt="Capture d&#39;écran 2026-05-11 182925" src="https://github.com/user-attachments/assets/889c82a7-5e3d-42ed-8538-daba57545129" /></td>
      <td valign="bottom"><img width=100% alt="image" src="https://github.com/user-attachments/assets/9066823b-47f9-45c6-bd90-0b2d233c3322" /></td>
      <td valign="bottom"><img width="611" height="640" alt="Capture d&#39;écran 2026-05-11 163710" src="https://github.com/user-attachments/assets/0fb3e763-3524-493e-bc53-375319dc395a" /></td>
  </table>
</div>
<div align="center">
  <table>
    <tr>
      <td valign="bottom"><img width=100% alt="Capture d&#39;écran 2026-05-11 165135" src="https://github.com/user-attachments/assets/7d583592-5eec-41d8-b5c6-1adae2806bec" /></td>
      <td valign="bottom"><img width=100% alt="Capture d&#39;écran 2026-05-11 165217" src="https://github.com/user-attachments/assets/9bfa6045-b343-4c8b-a260-0d9cf281aa54" />
</td>
  </table>
</div>  

<img width="250" height="450" alt="1" src="https://github.com/user-attachments/assets/433833a3-f714-46bb-8b1d-1418f47cb6e3" />
<img width="250" height="450" alt="1" src="https://github.com/user-attachments/assets/e5046007-6468-41a7-8c07-a12f6cb03de0" />


<br>

## Bill of Materials

Source: `BOM RC plane.csv`

|Product name        |Description                                              |Product Amount|Unit Price|Link                                                                                                                             |Total Price ( after discounts)|
|--------------------|---------------------------------------------------------|--------------|----------|---------------------------------------------------------------------------------------------------------------------------------|------------------------------|
|                    |                                                         |              |          |                                                                                                                                 |                              |
|Servo wires         |2 different wires to be used with the servos motors      |2             |1,61€    |https://fr.aliexpress.com/item/1005008268927795.html?spm=a2g0o.order_list.order_list_main.58.5b605e5bQ86yTz&gatewayAdapt=glo2fra |3,01 �                        |
|BL Motor            |Brushless motor with motor controller card               |1             |9,59 �    |https://fr.aliexpress.com/item/1005007417006124.html?spm=a2g0o.order_list.order_list_main.11.5b605e5bQ86yTz&gatewayAdapt=glo2fra |8,38 �                        |
|LiPo Battery        |11.1v with 2500 mAh each to feed the motor and servos    |2             |11,99 �   |https://fr.aliexpress.com/item/1005007176429068.html?spm=a2g0o.order_list.order_list_main.65.5b605e5bQ86yTz&gatewayAdapt=glo2fra |20,53 �                       |
|Carbon propeller    |A pair 1045 (better with small motor)                    |1             |3,09 �    |https://fr.aliexpress.com/item/1005008813878260.html?spm=a2g0o.order_list.order_list_main.83.5b605e5bQ86yTz&gatewayAdapt=glo2fra |2,67 �                        |
|Carbon propeller    |A pair 9047 (better with big motor)                      |1             |2,84 �    |https://fr.aliexpress.com/item/1005008813878260.html?spm=a2g0o.order_list.order_list_main.83.5b605e5bQ86yTz&gatewayAdapt=glo2fra |2,46 �                        |
|Brushless Motor     |A better brushless motor to improve the lift of the plane|1             |6,39 �    |https://fr.aliexpress.com/item/1005010025620096.html?spm=a2g0o.order_list.order_list_main.107.5b605e5bQ86yTz&gatewayAdapt=glo2fra|5,53 �                        |
|Little camera       |To be placed on the plane to record the flights          |1             |9,59 �    |https://fr.aliexpress.com/item/1005010222999155.html?spm=a2g0o.order_list.order_list_main.143.5b605e5bQ86yTz&gatewayAdapt=glo2fra|8,29 �                        |
|Sd card             |32 GO SD card for the camera                             |1             |3,89 �    |https://fr.aliexpress.com/item/1005009551797014.html?spm=a2g0o.order_list.order_list_main.131.5b605e5bQ86yTz&gatewayAdapt=glo2fra|3,40 �                        |
|1mm metal cable     |To link the servos and the wings for exemple             |1             |3,89 �    |https://fr.aliexpress.com/item/1005006401690836.html?spm=a2g0o.order_list.order_list_main.149.5b605e5bQ86yTz&gatewayAdapt=glo2fra|3,40 �                        |
|metal renforced tape|strong tape to put on the parts that need to be stronger |1             |4,29 �    |https://fr.aliexpress.com/item/1005010142077041.html?spm=a2g0o.order_list.order_list_main.155.5b605e5bQ86yTz&gatewayAdapt=glo2fra|3,71 �                        |
|glue stick          |to glue all the parts of the plane together              |1             |4,49 �    |https://fr.aliexpress.com/item/1005009667353037.html?spm=a2g0o.order_list.order_list_main.167.5b605e5bQ86yTz&gatewayAdapt=glo2fra|3,92 �                        |
|LiPo charger        |to charge the two batteries                              |1             |9,59 �    |https://fr.aliexpress.com/item/32860849974.html?spm=a2g0o.order_list.order_list_main.179.5b605e5bQ86yTz&gatewayAdapt=glo2fra     |8,38 �                        |
|                    |                                                         |              |          |                                                                                                                                 |                              |
|                    |                                                         |              |83,24 �   |                                                                                                                                 |73,68 �                       |




## You might also like

- [APX USB HUB](https://github.com/gabouin/APX-USB-HUB) - A PTC-secured USB HUB designed for [Macondo - Hack Club](https://macondo.hackclub.com)
- [HackPad](https://github.com/Gabouin/Hackpad) - A 6-keys macropad designed for [Blueprint - Hack Club](https://blueprint.hackclub.com)
- See more in my [github](https://github.com/gabouin)

## Contributing

Contributions, improvements, and remixes are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) guide to get started.

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.


## Credits

This project uses:

- **KiCad** - PCB design and schematic capture
- **JLCPCB** - PCB manufacturing
- **LCSC** - Parts order
- **Figma** - Silkscreen and banner design
- **Fusion 360** - CAD render
