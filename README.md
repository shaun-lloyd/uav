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
| Flight Controller  | The Cube Orange – Standard Set with ADS-B Carrier Board | <a href="http://www.proficnc.com/all-products/191-pixhawk2-suite.html" target="_blank">`proficnc`</a> | |
| Radio Transmittor | FrSky ACCST Taranis Q X7 Transmitter 2.4G 16CH Mode 2 | <a href="https://www.frsky-rc.com/product/taranis-q-x7-2/" target="_blank">`FrSky`</a> | |
| Radio Reciever | TBS Crossfire 8Ch Diversity Rx | <a href="https://www.team-blacksheep.com/products/prod:crossfire_8chrx" target="_blank">`TBS`</a> | |
| Antenna - Reciever | TBS Crossfire Tuned Rx Antenna 2pc | <a href="https://www.team-blacksheep.com/products/prod:tuned_rx_antenna" target="_blank">`TBS`</a> | |
| Radio | 915Mhz SiK Radio Telemetry BlueTooth adapter 500mW complete kit | <a href="https://droneshop.biz/product/915mhz-sik-radio-telemetry-bluetooth-adapter-500mw-complete-kit/?v=eedc0d4ce163" target="_blank">`droneshop`</a> |  |
| Radio Reciever | TBS Fusion | <a href="https://www.team-blacksheep.com/products/prod:tbs_fusion" target="_blank">`TBS`</a>  | |
| fpv goggles | ORQA FPV.ONE OLED FPV GOGGLES | <a href="https://orqafpv.com/" target="_blank">`orqafpv`</a> | |
| Antenna - video | TBS Fusion VAS Antenna Pack | <a href="https://www.team-blacksheep.com/products/prod:fusion_vasant_pack" target="_blank">`TBS`</a> | |
| Video Transmittor | TBS Unify Pro32 HV (MMCX) | <a href="https://www.team-blacksheep.com/products/prod:unifypro32_hv" target="_blank">`TBS`</a> | |
| Cam | RunCam Phoenix 2 Joshua Edition CAM 1/2 CMOS f2.0 Super WD | <a href="https://shop.runcam.com/runcam-phoenix-2/" target="_blank">`runcam`</a> | |
| Battery | URUAV 14.8V 10000mAh 30/60C 4S Lipo Battery XT90 | <a href="https://www.uruav.com/URUAV-14_8V-10000mAh-30-or-60C-4S-Lipo-Batteri-XT60-Plug-f-r-FPV-RC-Quadcopter-Jordbruk-Drone-p-224.html" target="_blank">`uruav`</a> | |
| LiDAR | Benewake TF02 PRO LiDAR Rangefinder (40m) | <a href="http://en.benewake.com/product/detail/5c345c9de5b3a844c4723299" target="_blank">`benewake`</a> | |

<details>
<summary>## The Cube Orange</summary>
The Cube Orange autopilot is the latest and most powerful model in the Cubepilot ecosystem.
Designed for hobby users, commercial system integrators and UAS manufacturers the Cube Orange 
autopilot is part of a wide ecosystem of autopilot modules and carrier boards. 

### ADS-B Carrier Board
* Integration of uAvonix ADS-B IN Receiver on Serial 5
* Built-In ADS-B Antenna
</details>

# Software

<details>
<summary>## Ardupilot</summary>

* [ardupilot-home] Home
* [ardupilot-plane] Plane

[ardupilot-home]: https://ardupilot.org/ardupilot/index.html
[ardupilot-plane]: https://ardupilot.org/plane/index.html

</details>

<details>
<summary>QGroundControl</summary>

* User Guide  https://docs.qgroundcontrol.com/en/
* Developer Guide https://dev.qgroundcontrol.com/en/

</details>

<details><summary>Mavlink</summary>

* <a href="https://mavlink.io/en/">Guide</a>
* <a href="https://mavsdk.mavlink.io/develop/en/index.html">SDK</a>
* <a href="https://mavlink.io/en/messages/common.html">Common Messages</a>
* <a href="http://mavsdk-python-docs.s3-website.eu-central-1.amazonaws.com">Python API Reference</a>
</details>

<details><summary>MavProxy</summary>

Home    https://ardupilot.org/mavproxy/index.html
Linux Dev Environment https://ardupilot.org/mavproxy/docs/development/mavdevenvlinux.html
Cheatsheat  https://ardupilot.org/mavproxy/docs/getting_started/cheatsheet.html#mavproxy-cheetsheet
Modules https://ardupilot.org/mavproxy/docs/modules/index.html
</details>

# Protocols

## Analog
<details><summary>PWM  Pulse Width Modulation.</summary>
* 1 channel.
* length of the pulse specifies the servo output or throttle position.
</details>

<details><summary>PPM,CPPM,PPMSUM  Pulse Postion Modulation.</summary>
* 8 channels.
* channels are sent one after the other.
* It’s not as accurate or jitter free as serial communications, but it’s more widely available and supported by many Flight controllers.
</details>

## Serial Protocols
* Digital loss-less.
* 3 wires (signal, power, ground).
* multiple channels.
* Serial Port required on reciever on FlightController

<details><summary>SBUS</summary>
Serial Bus.
* 18 channels.
* inverted UART communication signal.
</details>

<details><summary>CRSF Crossfire</summary>
* faster update rates
* two-way capabilities, no additional ports required.
</details>

<details><summary>## Frsky</summary>
* D8      D/V series.
* D16     X series.
* LR12    (longrange) L9R
</details>
