# UAV
My ardupilot uav project. I welcome any feedback, suggestions and guidance.
I have yet to recieve all the parts, this repo is just documenting my progress.

This project could not exist without the tireless work of the Ardupilot community under
the guidance of hacker legend Andrew Trigdell.

I want to thank the following for the help:
* [Lee Schofield](http://www.painless360.com/) 
* [Mark Qvale](http://www.itsqv.com/QVM/index.php?title=Main_Page)

<details><summary>Legal</summary>

[Drone Regulations](https://droneregulations.info/)
[CASA](https://www.casa.gov.au/knowyourdrone)

## Australia

* You must not fly your drone higher than 120 metres.
* You must keep your drone at least 30 metres away from other people.
* You must only fly one drone at a time.
* You must keep your drone within visual line-of-sight.
* You must not fly over or above people or in a populous area. This could include beaches, parks, events, or sport ovals where there is a game in progress.
* Respect personal privacy. Don’t record or photograph people without their consent — this may breach other laws.
* If your drone weighs more than 100 grams, you must fly at least 5.5 kilometres away from a controlled airport, which generally have a control tower at them.
* You must only fly during the day and you must not fly through cloud or fog.
* You must not fly your drone over or near an area affecting public safety or where emergency operations are underway. 
* If you're near a helicopter landing site or smaller aerodrome without a control tower, you can fly your drone within 5.5 kilometres.
If you become aware of manned aircraft nearby, you will have to manoeuvre away and land your drone as quickly and safely as possible.

### FPV
* You do not need CASA approval if you only intend to operate FPV indoors for recreational purposes.
* Flying FPV outdoors is only permitted with CASA approval. This applies to both recreational and commercial drone users.
* [Apply for CASA Recreational FPV approval](https://www.casa.gov.au/drones/rules/restricted-airspace-permissions-and-approvals-recreational-operators)
* [Apply for EVLOS Extended Visual Line of Sight](https://www.casa.gov.au/drones/reoc/additional-approvals#visual-line-of-sight-civil-aviation-safety-regulations-101-073-)

#### Applications
* [Apply for Aviation Reference Number](https://www.casa.gov.au/licences-and-certification/individual-licensing/applying-aviation-reference-number-arn)
* [Model Airflight Authorisation](https://www.casa.gov.au/files/model-aircraft-flight-authorisation-area-approval-formpdf)
* [Airspace Risk Assessment Template](https://www.casa.gov.au/files/form-1589)
* A map with an aerial view of the location, such as a screenshot from Google Earth or a diagram, displaying the required information
* Participate in an interview and/or practical flight test, if required.
</details>

# Community
[ Ardupilot ](https://discuss.ardupilot.org/)
[ DIYDRONES ](https://diydrones.com/)

# Hardware
| Component | Device | Manufacturer | Manual | 
| --- | --- | --- | --- |
| Plane | X-UAV Mini Talon aircraft FPV | <a href="http://www.x-uav.cn/en/content/?465.html" target="_blank">`x-uav`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/xuav-mini_talon.pdf">manual</a>| 
| Motor | SunnySky X2212-III KV980 KV1250 KV1400 3-4S Long Shaft Outrunner Brushless Motor | <a href="https://sunnyskyusa.com/products/sunnsky-x2212" target="_blank">`SunnySky`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/sunnysky-1400.pdf">manual</a> |
| ESC | ZTW Mantis Slim 40A SBEC Brushless ESC Speed Controller | <a href="https://www.ztwoem.com/product/mantis-slim-series/" target="_blank">`mantis`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/ztw-mantis.pdf">manual</a> |
| Propellor | | <a href="" target="_blank">``</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/.pdf"></a> |
| Servo | Racerstar MG90S 9g Micro Metal Gear Analog Servo | <a href="http://m.racerstar.com/4pcs-racerstar-mg90s-9g-micro-metal-gear-analog-servo-for-450-rc-helicopter-rc-car-boat-robot-p-367.html" target="_blank">`Racerstar`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/servo-MG90S.pdf">manual</a> |
| Battery | URUAV 14.8V 10000mAh 30/60C 4S Lipo Battery XT90 | <a href="https://www.uruav.com/URUAV-14_8V-10000mAh-30-or-60C-4S-Lipo-Batteri-XT60-Plug-f-r-FPV-RC-Quadcopter-Jordbruk-Drone-p-224.html" target="_blank">`uruav`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/.pdf"></a> |
| Flight Controller | | | |
| Flight Controller Carrier Board  | Pixhawk2.1 with ADS-B | <a href="https://docs.cubepilot.org/user-guides/carrier-boards/ads-b-carrier-board" target="_blank">`cubepilot`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/pixhawk2.pdf">manual</a> |
| Flight Controller Sensors  |  Cube Orange | <a href="">`Cube Orange`</a> | |
| Companion | RPI Zero | <a href="https://www.raspberrypi.org/products/raspberry-pi-zero/">`RPI`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/rpi-zero.pdf">`manual`</a> |
| Sensors | | | 
| LiDAR | Benewake TF02 PRO LiDAR Rangefinder (40m) | <a href="http://en.benewake.com/product/detail/5c345c9de5b3a844c4723299">`benewake`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/benewake-TF02.pdf">manual</a> |
| Radio | | | |
| Tx | FrSky ACCST Taranis Q X7 Transmitter 2.4G 16CH Mode 2 | <a href="https://www.frsky-rc.com/product/taranis-q-x7-2/" target="_blank">`FrSky`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/taranis-qx7.pdf">manual</a> |
| Rx | TBS Crossfire 8Ch Diversity Rx | <a href="https://www.team-blacksheep.com/products/prod:crossfire_8chrx" target="_blank">`TBS`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/tbs-crossfire.pdf">manual</a> |
| Rx | FrSky X8R | <a href="https://www.frsky-rc.com/product/x8r/" target="_blank">`FrSky`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/frsky-reciever-x8r.pdf">manual</a> |
| Rx | TBS Fusion | <a href="https://www.team-blacksheep.com/products/prod:tbs_fusion" target="_blank">`TBS`</a>  | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/tbs-fusion.pdf">manual</a> |
| Rx | 915Mhz SiK Radio Telemetry BlueTooth adapter 500mW complete kit | <a href="https://droneshop.biz/product/915mhz-sik-radio-telemetry-bluetooth-adapter-500mw-complete-kit/?v=eedc0d4ce163" target="_blank">`droneshop`</a> |  <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/.pdf">manual</a> |
| Rx Sat | RockBLOCK 9603 | <a href="https://www.rock7.com/products/rockblock-9603-compact-plug-play-satellite-transmitter">`ROCKBLOCK 19603`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/rockblock-9603.pdf">manual</a> |
| Rx_Antenna | TBS Fusion VAS Antenna Pack | <a href="https://www.team-blacksheep.com/products/prod:fusion_vasant_pack" >`TBS`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/.pdf">manual</a> |
| Rx_Antenna | TBS Crossfire Tuned Rx Antenna 2pc | <a href="https://www.team-blacksheep.com/products/prod:tuned_rx_antenna" target="_blank">`TBS`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/tbs-crossfire.pdf">manual</a> |
| FPV | | | |
| fpv goggles | ORQA FPV.ONE OLED FPV GOGGLES | <a href="https://orqafpv.com/" target="_blank">`orqafpv`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/orqa-fpvone-1.2.b.pdf">manual</a> |
| Cam | RunCam Phoenix 2 Joshua Edition CAM 1/2 CMOS f2.0 Super WD | <a href="https://shop.runcam.com/runcam-phoenix-2/">`runcam`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/.pdf">manual</a> |
| OSD | MinimOSD | <a href="">`MinimOSD`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/minimosd.pdf"></a> |
| Fuse | TBS Smoke Stopper | <a href="">`tbs-smoke-stopper`</a> | | 

# Materials
| Material | Function | Supplier | Spec |
| --- | --- | --- |
| d3o | Impact / Vibration | <a href="">`gamebreaker`</a> | <a href="https://github.com/shaun-lloyd/uav/blob/master/manual/"></a> |
| carbonhinge | Control Surfaces | <a href="https://www.carbonhinge.com/">`carbonhinge`</a> | |
| Stratocell Whisper | Form / Sound Proofing | <a href="">`tmp`</a> | |
| Carbonfiber | Form / Strength | <a href=""></a> | |
| Kevlar | Strength | <a href=""></a> | |

# Plastics
| Name | Name_Long | Function | Desc | Negatives |
| --- | --- | --- | --- | --- |
| ABS | Acrylonitrile Butadiene Styrene | all-round electrical enclosures | | exposed to sunlight for prolonged periods degrades | 
| PMMA | Polymethyl Methacrylate Plexiglas | Infared transparent | Light transmission of up to 92 per cent. | britle |
| ASA+PC Blend Acrylonitrile Styrene Acrylester and Polycarbonate | high temp / impact strength & chemical / weather & flame resitant UL 94 V-0 | ? | |
| PA | Polyamide | tough, wear-resistant and has good sliding properties | absorb moisture | |
| PC+ABS Blend | Polycarbonate + Acrylonitrile Butadiene Styrene | sub-zero temperatures / chemical resistance |

# Tools
| Component | Device | Manual |
| --- | --- | --- |
| Battery Charger | | |
| Battery Tester | | |
| CNC | <a href="https://synthetos.com/">`synthetos`</a> | |
| RF meter | ImmersionRC RF Power Meter V2 | <a href="https://docs.google.com/document/d/1MHtkZg81mqF2xibuO7tHb-OH-l9ib3NImpGnRQWFtBo/edit">manual</a> |

<details><summary>Hacks</summary>
<details><summary>Taranis QX7 - CRSF MOD</summary>
[ TBS ](https://www.team-blacksheep.com/products/prod:qx7mod)
</details>
</details>

<details><summary>The Cube Orange</summary>
The Cube Orange autopilot is the latest and most powerful model in the Cubepilot ecosystem.
Designed for hobby users, commercial system integrators and UAS manufacturers the Cube Orange 
autopilot is part of a wide ecosystem of autopilot modules and carrier boards. 

## Processor
* 32bit ARM® STM32H743 Cortex®-M7（with DP-FPU）
* 400 Mhz/1 MB RAM/2 MB Flash
* 32 bit STM32F103 failsafe co-processor
## Sensors
* Three redundant IMUs (accels, gyros and compass)
* ICM 20649 integrated accelerometer / gyro, MS5611 barometer on base board
* InvenSense ICM20602 IMU,ICM20948 IMU/MAG, MS5611 barometer on temperature controlled, vibration isolated board
* All sensors connected via SPI.
## Power
* Redundant power supply with automatic failover
* Servo rail high-power (7 V) and high-current ready
* All peripheral outputs over-current protected, all inputs ESD protected
## Interfaces
* 14x PWM servo outputs (8 from IO, 6 from FMU)
* S.Bus servo output
* R/C inputs for CPPM, Spektrum / DSM and S.Bus
* Analogue / PWM RSSI input
* 5x general purpose serial ports, 2 with full flow control
* 2x I2C ports
* SPI port (un-buffered, for short cables only not recommended for use)
* 2x CAN Bus interface
* 3x Analogue inputs (3.3V and 6.6V)
* High-powered piezo buzzer driver (on expansion board)
* High-power RGB LED (I2C driver compatible connected externally only)
* Safety switch / LED
* Optional carrier board for Intel Edison (now obsolete)

</details>

<details><summary>ADS-B Carrier Board</summary>
* Integration of uAvonix ADS-B IN Receiver on Serial 5
* Built-In ADS-B Antenna

## TELEM1, TELEM2 ports
| Pin | Color | Signal | Volt |
| :---: | :---: | :---: | :---: |
| 1 | red | VCC | +5 |
| 2 | blk | TX (OUT) | +3.3 |
| 3 | blk | RX (IN) | +3.3 |
| 4 | blk | CTS | +3.3 |
| 5 | blk | RTS | +3.3 |
| 6 | blk | GND | GND |

## GPS1 port
| Pin | Color | Signal | Volt |
| :---: | :---: | :---: | :---: |
| 1 | red | VCC | +5 |
| 2 | blk | TX (OUT) | +3.3 |
| 3 | blk | RX (IN) | +3.3 |
| 4 | blk | SCL I2C1 | +3.3 |
| 5 | blk | SDA I2C1 | +3.3 |
| 6 | blk | Button | GND |
| 7 | blk | button LED | GND |
|  | blk | GND | GND |

## GPS2 port
| Pin | Color | Signal | Volt |
| :---: | :---: | :---: | :---: |
| 1 | red | VCC | +5 |
| 2 | blk | TX (OUT) | +3.3 |
| 3 | blk | RX (IN) | +3.3 |
| 4 | blk | SCL I2C2 | +3.3 |
| 5 | blk | SDA I2C2 | +3.3 |
| 6 | blk | GND | GND |

## ADC
| Pin | Color | Signal | Volt |
| :---: | :---: | :---: | :---: |
| 1 | red | VCC | +5 |
| 2 | blk | ADC IN | |
| 3 | blk | GND | GND |

## I2C2
| Pin | Color | Signal | Volt |
| :---: | :---: | :---: | :---: |
| 1 | red | VCC | +5 |
| 2 | blk | SCL | +3.3 (pullups) |
| 3 | blk | SDA | +3.3 (pullups) |
| 4 | blk | GND | GND |

## CAN1&2
| Pin | Color | Signal | Volt |
| :---: | :---: | :---: | :---: |
| 1 | red | VCC | +5 |
| 2 | blk | CAN_H | +12 |
| 3 | blk | CAN_L | +12 |
| 4 | blk | GND | GND |

## POWER1&2
| Pin | Color | Signal | Volt |
| :---: | :---: | :---: | :---: |
| 1 | red | VCC | +5 |
| 2 | red | VCC | +5 |
| 3 | blk | CURRENT | up to +3.3 |
| 4 | blk | VOLTAGE | up to +3.3 |
| 5 | blk | GND | GND |
| 6 | blk | GND | GND |

## USB
| Pin | Color | Signal | Volt |
| :---: | :---: | :---: | :---: |
| 1 | red | VCC | +5 |
| 2 | blk | D_plus | +3.3 |
| 3 | blk | D_minus  | +3.3 |
| 4 | blk | GND | GND |
| 5 | blk | BUZZER | battery voltage |
| 6 | blk | Boot/Error LED | |

</details>

<details><summary>RPI Zero</summary>

* [Config](https://www.raspberrypi.org/documentation/configuration/)
* [Hardware](https://www.raspberrypi.org/documentation/hardware/raspberrypi/README.md)
</details>

# Software

<details><summary>Open Tx</summary>

* [Home](https://www.open-tx.org/)
* [Manual](https://opentx.gitbooks.io/manual-for-opentx-2-2/content/)
* [Docs](https://legacy.gitbook.com/@opentx)
* [git](https://github.com/opentx/opentx)

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
</details>

<details><summary>Yappu Telemetry</summary>

a LUA telemetry script for the Frsky Horus and Taranis radios using the ArduPilot frsky passthru telemetry protocol.

* [git](https://github.com/yaapu/FrskyTelemetryScript)
</details>

<details>
<summary>Ardupilot</summary>
ArduPilot enables the creation and use of trusted, autonomous, unmanned vehicle systems for the peaceful benefit of all. ArduPilot provides a comprehensive suite of tools suitable for almost any vehicle and application. As an open source project, it is constantly evolving based on rapid feedback from a large community of users. The Development Team works with the community and commercial partners to add functionality to ArduPilot that benefits everyone. Although ArduPilot does not manufacture any hardware, ArduPilot firmware works on a wide variety of different hardware to control unmanned vehicles of all types. Coupled with ground control software, unmanned vehicles running ArduPilot can have advanced functionality including real-time communication with operators. ArduPilot has a huge online community dedicated to helping users with questions, problems, and solutions

* [Home](https://ardupilot.org/ardupilot/index.html)
* [Plane](https://ardupilot.org/plane/index.html)
* [Build Setup](https://ardupilot.org/dev/docs/building-setup-linux.html#building-setup-linux)
* [Build Instructions](https://github.com/ArduPilot/ardupilot/blob/master/BUILD.md)
* [Radio Control Calibration](https://ardupilot.org/copter/docs/common-radio-control-calibration.html#common-radio-control-calibration)
* [ESC Calibration](https://ardupilot.org/copter/docs/esc-calibration.html)
* [WAF](https://waf.io/)
* [WAF-book](https://waf.io/book/)
* [Submittion Guide](https://ardupilot.org/dev/docs/submitting-patches-back-to-master.html#submitting-patches-back-to-master)
* [Style Guide](https://ardupilot.org/dev/docs/style-guide.html#style-guide)

### Submission cs
* Commit Message
```sh
Subsystem: brief description

Longer description...
```
* Clean up your local commit history
```sh
git rebase -i "HEAD~10"
```


### Setup Docker
```sh
git clone https://github.com/your-github-userid/ardupilot
cd ardupilot
git submodule update --init --recursive

docker build . -t ardupilot

docker run --rm -it -v `pwd`:/ardupilot ardupilot:latest bash
```

### Build
```sh
./waf configure
./waf 

./waf --targets bin/arduplane --upload
```
</details>

<details>
<summary>QGroundControl</summary>

QGroundControl provides full flight control and mission planning for any MAVLink enabled drone.
Its primary goal is ease of use for professional users and developers. All the code is open-source source, so you can contribute and evolve it as you want.

* [Home](http://qgroundcontrol.com/)
* [User Guide](https://docs.qgroundcontrol.com/en/)
* [Dev Guide](https://dev.qgroundcontrol.com/en/)
* [Download](https://docs.qgroundcontrol.com/en/getting_started/download_and_install.html)
</details>

<details>
<summary>MavProxy</summary> 
A UAV ground station software package for MAVLink based systems

MAVProxy is a fully-functioning GCS for UAV’s, designed as a minimalist, portable and extendable GCS for any autonomous system supporting the MAVLink protocol (such as one using ArduPilot). MAVProxy is a powerful command-line based “developer” ground station software. It can be extended via add-on modules, or complemented with another ground station, such as Mission Planner, APM Planner 2, QGroundControl etc, to provide a graphical user interface.

* [Home](https://ardupilot.org/mavproxy/index.html)
* [Linux Dev Environment](https://ardupilot.org/mavproxy/docs/development/mavdevenvlinux.html)
* [Cheatsheet](https://ardupilot.org/mavproxy/docs/getting_started/cheatsheet.html#mavproxy-cheetsheet)
* [Modules](https://ardupilot.org/mavproxy/docs/modules/index.html)
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

* [Home](https://mavsdk.mavlink.io/develop/en/index.html)
* [Python](https://github.com/mavlink/MAVSDK-Python#mavsdk-python)
* [Python Examples](https://github.com/mavlink/MAVSDK-Python/tree/master/examples) 
* [Python API Reference](http://mavsdk-python-docs.s3-website.eu-central-1.amazonaws.com/)
</details>

# Protocols

<details>
<summary>Mavlink</summary>

MAVLink is a binary telemetry protocol designed for resource-constrained systems and bandwidth-constrained links.
MAVLink is deployed in two major versions: v1.0 and v2.0, which is backwards-compatible (v2.0 implementations can parse and send v1.0 packets). 
Telemetry data streams are sent in a multicast design while protocol aspects that change the system configuration,
and require guaranteed delivery like the mission protocol or parameter protocol are point-to-point with retransmission.

* [Guide] (https://mavlink.io/en/)
* [SDK] (https://mavsdk.mavlink.io/develop/en/index.html)
* [Common Messages](https://mavlink.io/en/messages/common.html)
* [Python API Reference](http://mavsdk-python-docs.s3-website.eu-central-1.amazonaws.com)
</details>

<details>
<summary>PWM</summary>
Pulse Width Modulation.

* analog.
* 1 channel.
* length of the pulse specifies the servo output or throttle position.
</details>

<details>
<summary>PPM</summary>
Pulse Postion Modulation

* analog.
* 8 channels.
* channels are sent one after the other.
* It’s not as accurate or jitter free as serial communications.
</details>

<details><summary>SBUS</summary>
Serial Bus.

* digital loss-less.
* 18 channels.
* inverted UART communication signal.
</details>

<details><summary>CRSF</summary>
Crossfire Serial F?

* digital loss-less.
* faster update rates
* two-way capabilities, no additional ports required.
</details>

<details><summary>I2C</summary>
Inter-Integrated Circuit

* serial
* multi-master, multi-slave, packet switched, single-ended.
</details>

<details>
<summary>SPI</summary>
Serial Peripheral Interface

* synchronous serial. 
</details>

<details>
<summary>F-Port</summary>
FPort is a bi-directional protocol, using SBus RC in one direction, and serial telemetry in the other. The RC portion can be decoded when attached to an autopilot as if it were SBus, but the embedded telemetry would be lost. See the FPort setup documentation for details on connection to one of the autopilots Serial Ports.

</details>


Device

<details><summary>UART</summary>
A universal asynchronous receiver-transmitter a hardware device for asynchronous serial communication in which the data format and transmission speeds are configurable.
The electric signaling levels and methods are handled by a driver circuit external to the UART.
A UART is usually an individual (or part of an) integrated circuit (IC) used for serial communications over a computer or peripheral device serial port.
One or more UART peripherals are commonly integrated in microcontroller chips.

A related device, the universal synchronous and asynchronous receiver-transmitter (USART) also supports synchronous operation. 
</details>

