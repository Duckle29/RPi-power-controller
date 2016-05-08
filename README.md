# RPi-power-controller

The RPi-power-controller is a small, ATTiny85 based power controller,
that talks to a RPi over software serial, via the hardware serial port,
and issues a shutdown command.

There are plans to support custom commands, by sending the desired command to
the board from the rpi.

The board also features two 10A SPDT relays, intended to be used to break both live and neutral, to safely handle schuko style plugs, but could be used in parallel to handle larger loads.

TODO:
* BOM
* Firmware

### Images
Here's some renders of the board to be

[PCB-top]: https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/1f80f6248889095e2f93bf03f451f997.png "Top side of the PCB"
[PCB-bot]: https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/245595cf08f88fd80672bb5110447598.png "Bottom side of the PCB"

They are rather large :/

![PCB top side][PCB-top]
![PCB bottom side][PCB-bot]
