# UAV
My ardupilot uav project. I welcome any feedback, suggestions and guidance.
I have yet to recieve all the parts, this repo is just documenting my progress.

This project could not exist without the tireless work of the Ardupilot community under
the guidance of hacker legend Andrew Trigdell.

I want to thank Lee Schofield of painless360 for his wealth of tutorials and guidance. 

# Hardware

| Component | Device | Manufacturer | Manual | 
| :---: | :---: | :---: | :---: |
| Plane | ZOHD Nano Talon EVO 860mm Wingspan AIO V-Tail EPP FPV | <a href="https://au.banggood.com/ZOHD-Nano-Talon-EVO-860mm-Wingspan-AIO-V-Tail-EPP-FPV-Wing-RC-Airplane-PNPWith-FPV-Ready-p-1564933.html?ID=533302&cur_warehouse=AU" target="_blank">`banggood`</a> | |
| Flight Controller  | The Cube Orange – Standard Set with ADS-B Carrier Board | <a href="https://ardupilot.org/plane/docs/common-thecubeorange-overview.html" target="_blank">`proficnc`</a> | |
| Radio Transmittor | FrSky ACCST Taranis Q X7 Transmitter 2.4G 16CH Mode 2 | <a href="https://www.frsky-rc.com/product/taranis-q-x7-2/" target="_blank">`FrSky`</a> | |
| Radio Reciever | TBS Crossfire 8Ch Diversity Rx | <a href="https://www.team-blacksheep.com/products/prod:crossfire_8chrx" target="_blank">`TBS`</a> | |
| Radio Reciever | FrSky X8R | <a href="https://www.frsky-rc.com/product/x8r/" target="_blank">`FrSky`</a> | |
| Antenna - Reciever | TBS Crossfire Tuned Rx Antenna 2pc | <a href="https://www.team-blacksheep.com/products/prod:tuned_rx_antenna" target="_blank">`TBS`</a> | |
| Radio | 915Mhz SiK Radio Telemetry BlueTooth adapter 500mW complete kit | <a href="https://droneshop.biz/product/915mhz-sik-radio-telemetry-bluetooth-adapter-500mw-complete-kit/?v=eedc0d4ce163" target="_blank">`droneshop`</a> |  |
| Radio Reciever | TBS Fusion | <a href="https://www.team-blacksheep.com/products/prod:tbs_fusion" target="_blank">`TBS`</a>  | |
| fpv goggles | ORQA FPV.ONE OLED FPV GOGGLES | <a href="https://orqafpv.com/" target="_blank">`orqafpv`</a> | |
| Antenna - video | TBS Fusion VAS Antenna Pack | <a href="https://www.team-blacksheep.com/products/prod:fusion_vasant_pack" target="_blank">`TBS`</a> | |
| Video Transmittor | TBS Unify Pro32 HV (MMCX) | <a href="https://www.team-blacksheep.com/products/prod:unifypro32_hv" target="_blank">`TBS`</a> | |
| Cam | RunCam Phoenix 2 Joshua Edition CAM 1/2 CMOS f2.0 Super WD | <a href="https://shop.runcam.com/runcam-phoenix-2/" target="_blank">`runcam`</a> | |
| Battery | URUAV 14.8V 10000mAh 30/60C 4S Lipo Battery XT90 | <a href="https://www.uruav.com/URUAV-14_8V-10000mAh-30-or-60C-4S-Lipo-Batteri-XT60-Plug-f-r-FPV-RC-Quadcopter-Jordbruk-Drone-p-224.html" target="_blank">`uruav`</a> | |
| LiDAR | Benewake TF02 PRO LiDAR Rangefinder (40m) | <a href="http://en.benewake.com/product/detail/5c345c9de5b3a844c4723299" target="_blank">`benewake`</a> | |

# Tools
| Component | Device | Manual |
| :---: | :---: | :---: |
| Battery Charger | | |
| Battery Tester | | |
| RF meter | ImmersionRC RF Power Meter V2 | <a href="https://docs.google.com/document/d/1MHtkZg81mqF2xibuO7tHb-OH-l9ib3NImpGnRQWFtBo/edit">manual</a> |

<details><summary>Hacks</summary>

<details><summary>Taranis QX7 - CRSF MOD</summary>
* [ TBS ]:  https://www.team-blacksheep.com/products/prod:qx7mod
</details>
</details>

<details><summary>The Cube Orange</summary>
The Cube Orange autopilot is the latest and most powerful model in the Cubepilot ecosystem.
Designed for hobby users, commercial system integrators and UAS manufacturers the Cube Orange 
autopilot is part of a wide ecosystem of autopilot modules and carrier boards. 

### ADS-B Carrier Board
* Integration of uAvonix ADS-B IN Receiver on Serial 5
* Built-In ADS-B Antenna
</details>

# Software

<details><summary>Open Tx</summary>

## FIRMWARE
OpenTX is open source firmware for RC radio transmitters. 
The firmware is highly configurable and brings much more features than found in traditional radios. 
The daily feedback from the thousands of users ensures the continued stability and quality of the firmware.

## COMPANION
The team also develops the OpenTX Companion transmitter support software.
OpenTX Companion is used for many different tasks like loading OpenTX firmware to the radio, backing up model settings, editing settings and running radio simulators.
OpenTX Companion is available for Windows, Apple OSX and Linux.

## SOUND
There are two applications available for creating and managing the soundfiles used by OpenTX.
OpenTX Speaker is used to generate voice files for OpenTX by using synthetic speech. OpenTX Recorder is used to record voice files via a microphone.
Both programs can generate sound files for all OpenTX voice languages. Every radio message, including system messages, can be changed.
OpenTX Speaker and OpenTXRecorder are available for Windows7.

- [ Home ]: https://www.open-tx.org/
- [ Manual ]: https://opentx.gitbooks.io/manual-for-opentx-2-2/content/
- [ Docs ]: https://legacy.gitbook.com/@opentx
- [ git ]: https://github.com/opentx/opentx
</details>

<details>
<summary>Ardupilot</summary>
ArduPilot enables the creation and use of trusted, autonomous, unmanned vehicle systems for the peaceful benefit of all. ArduPilot provides a comprehensive suite of tools suitable for almost any vehicle and application. As an open source project, it is constantly evolving based on rapid feedback from a large community of users. The Development Team works with the community and commercial partners to add functionality to ArduPilot that benefits everyone. Although ArduPilot does not manufacture any hardware, ArduPilot firmware works on a wide variety of different hardware to control unmanned vehicles of all types. Coupled with ground control software, unmanned vehicles running ArduPilot can have advanced functionality including real-time communication with operators. ArduPilot has a huge online community dedicated to helping users with questions, problems, and solutions

* [home]: https://ardupilot.org/ardupilot/index.html
* [plane]: https://ardupilot.org/plane/index.html
</details>

<details>
<summary>QGroundControl</summary>

QGroundControl provides full flight control and mission planning for any MAVLink enabled drone.
Its primary goal is ease of use for professional users and developers. All the code is open-source source, so you can contribute and evolve it as you want.

- [ Home ]: http://qgroundcontrol.com/
- [ User Guide ]: https://docs.qgroundcontrol.com/en/
- [ Dev Guide ]: https://dev.qgroundcontrol.com/en/
- [ Download ]: https://docs.qgroundcontrol.com/en/getting_started/download_and_install.html
</details>

<details>
<summary>MavProxy</summary> 
A UAV ground station software package for MAVLink based systems

MAVProxy is a fully-functioning GCS for UAV’s, designed as a minimalist, portable and extendable GCS for any autonomous system supporting the MAVLink protocol (such as one using ArduPilot). MAVProxy is a powerful command-line based “developer” ground station software. It can be extended via add-on modules, or complemented with another ground station, such as Mission Planner, APM Planner 2, QGroundControl etc, to provide a graphical user interface.

- [Home]: https://ardupilot.org/mavproxy/index.html
- [Linux Dev Environment]: https://ardupilot.org/mavproxy/docs/development/mavdevenvlinux.html
- [Cheatsheet]: https://ardupilot.org/mavproxy/docs/getting_started/cheatsheet.html#mavproxy-cheetsheet
- [Modules]: https://ardupilot.org/mavproxy/docs/modules/index.html
</details>

<details>
<summary>MavSDK</summary>
The easiest way to control Drones using MAVLink.
The MAVSDK is a MAVLink Library with APIs for C++, iOS, Python and Android.

The library provides a simple API for managing one or more vehicles, providing programmatic access to vehicle information and telemetry,
and control over missions, movement and other operations.

The library can run on a vehicle-based companion computer or on a ground-based GCS or mobile device (these devices have significantly more 
processing power that an ordinary flight controller, enabling tasks like computer vision, obstacle avoidance, and route planning).

Developers can extend the core C++ SDK using plugins in order to add any other required MAVLink API 
(for example, to integrate a flight controller with custom cameras, gimbals, or other hardware over MAVLink).

Cross-platform wrappers for the core library are actively being developed. These (primarily) use gRPC and Reactive Extensions.

- [ Home ]: https://mavsdk.mavlink.io/develop/en/index.html
- [ Python ]: https://github.com/mavlink/MAVSDK-Python#mavsdk-python
- [ Python_-Example]: https://github.com/mavlink/MAVSDK-Python/tree/master/examples
- [ Python API Reference ]: http://mavsdk-python-docs.s3-website.eu-central-1.amazonaws.com/
</details>
# Protocols

<details>
<summary>Mavlink</summary>

MAVLink is a binary telemetry protocol designed for resource-constrained systems and bandwidth-constrained links.
MAVLink is deployed in two major versions: v1.0 and v2.0, which is backwards-compatible (v2.0 implementations can parse and send v1.0 packets). 
Telemetry data streams are sent in a multicast design while protocol aspects that change the system configuration,
and require guaranteed delivery like the mission protocol or parameter protocol are point-to-point with retransmission.

- <a href="https://mavlink.io/en/">Guide</a>
- <a href="https://mavsdk.mavlink.io/develop/en/index.html">SDK</a>
- <a href="https://mavlink.io/en/messages/common.html">Common Messages</a>
- <a href="http://mavsdk-python-docs.s3-website.eu-central-1.amazonaws.com">Python API Reference</a>
</details>

<details>
<summary>PWM</summary>
Pulse Width Modulation.

- analog.
- 1 channel.
- length of the pulse specifies the servo output or throttle position.
</details>

<details>
<summary>PPM</summary>
Pulse Postion Modulation

- analog.
- 8 channels.
- channels are sent one after the other.
- It’s not as accurate or jitter free as serial communications.
</details>

<details><summary>SBUS</summary>
Serial Bus.

- digital loss-less.
- 18 channels.
- inverted UART communication signal.
</details>

<details><summary>CRSF</summary>
Crossfire Serial F?

- digital loss-less.
- faster update rates
- two-way capabilities, no additional ports required.
</details>

<details><summary>I2C</summary>
Inter-Integrated Circuit

- serial
- multi-master, multi-slave, packet switched, single-ended.
</details>

<details>
<summary>SPI</summary>
Serial Peripheral Interface

- synchronous serial. 
</details>

Device

<details><summary>UART</summary>
A universal asynchronous receiver-transmitter a hardware device for asynchronous serial communication in which the data format and transmission speeds are configurable.
The electric signaling levels and methods are handled by a driver circuit external to the UART.
A UART is usually an individual (or part of an) integrated circuit (IC) used for serial communications over a computer or peripheral device serial port.
One or more UART peripherals are commonly integrated in microcontroller chips.

A related device, the universal synchronous and asynchronous receiver-transmitter (USART) also supports synchronous operation. 
</details>

