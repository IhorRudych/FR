# Axcend Focus LC Firmware

This project contains the low-level firmware for controlling the Axcend Focus LC instrument.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

### Compiling

If you are running an Ubuntu host:

```
apt-get install gcc-arm-none-noeabi
```

### Deploying

[OpenOCD]()

If you are running an Ubuntu host:

```
apt-get install openocd
```

## Built With

* [ChibiOS RT](https://www.chibios.org)

## Versioning

We use [gitlab](https://gitlab.com) for versioning. For the versions available, see the [tags on this repository](https://gitlab.com/Tranxend/Firmware/tags).

## Modules

chconf.h
halconf.h
mcuconf.h


debug.h

ads101x.h
tmc2660.h


usbcfg.h

project.h

valve.h
packets.h
dispatch.h
daq.h
pump.h
handlers.h
settings.h

spi.h
# FR
