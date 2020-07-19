# Radio Protocols
This is a simple list of all communications protocols within uav system.

# Definitions
Tx  = Radio Transmittor
Rx  = Radio Reciever
FC  = Flight Controller

Tx <-> TX protocols <-> Rx <-> RX protocols <-> FC

# Rx protocols

## PWM  Pulse Width Modulation. 
- analog
- 1 channel.
- length of the pulse specifies the servo output or throttle position.

## PPM,CPPM,PPMSUM  Pulse Postion Modulation.
- analog
- 8 channels.
- channels are sent one after the other.
- It’s not as accurate or jitter free as serial communications, but it’s more widely available and supported by many Flight controllers.

## PCM  Pulse Code Modulation.
- digital, similar to PPM
- Signal error detection even error correction.
- it is more reliable and less susceptible to interference, but additional conversion is required so the equipment tends to be more expensive.


# Serial Protocols
- Digital loss-less.
- 3 wires (signal, power, ground).
- multiple channels.
- Serial Port required on reciever on FlightController

## SBUS
Serial Bus.
- 18 channels.
- inverted UART communication signal.

## IBUS
- two-way.
- One port servo / one port sensors

## XBUS
- 14 channels. 
- One of the advantages is the tiny time delay between each channel.

## MSP  Multiwii Serial Protocol
MSP commands as the RC input and it supports 8 channels in one signal cable.

## SUMD 
- like SBUS
- no signal invertor, better resolution of jitter

## CRSF Crossfire.
- faster update rates
- two-way capabilities, no additional ports required.

## FPort
FPort is a new RX protocol developed by Frsky and Betaflight developers. It combines both the control signal and telemetry data into 1 single wire which makes it more compact and easier to manage.


# Tx protocols

## Frsky
D8      D/V series.
D16     X series.
LR12    (longrange) L9R

## FlySky
AFHDS
AFHDS2A

## Spektrum
DSM
DSM2
DSMX

## Hitec
A-FHSS

## Futaba
FASST
