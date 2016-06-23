#Led Actuator Application

This application registers Flow, Flow Access, Light Control object and toggle Led on receiving Button press event.

How To Compile

Assuming you have creator-contiki source code with directories constrained-os, packages/led-actuator, packages/libobjects and packages/AwaLWM2M

To build with TI CC2520 6lowpan driver
```
$ cd led-actuator
$ make TARGET=mikro-e USE_CC2520=1
```

To build for Cascoda CA8210 6lowpan driver
```
$ cd led-actuator
$ make TARGET=mikro-e USE_CA8210=1

