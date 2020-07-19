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


# Serial Protocols
- Digital loss-less.
- 3 wires (signal, power, ground).
- multiple channels.
- Serial Port required on reciever on FlightController

## SBUS
Serial Bus.
- 18 channels.
- inverted UART communication signal.

## CRSF Crossfire.
- faster update rates
- two-way capabilities, no additional ports required.

# Tx protocols

## Frsky
D8      D/V series.
D16     X series.
LR12    (longrange) L9R
