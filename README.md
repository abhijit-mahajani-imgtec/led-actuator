#Led Actuator Application

This application registers Flow, Flow Access, Light Control object and toggle Led on receiving Button press event.

How To Compile

Assuming you have creator-contiki source code with directories constrained-os, packages/led-actuator, packages/libobjects and packages/AwaLWM2M

```
$ cd led-actuator
$ make TARGET=mikro-e
```

This will generate hex file which can be flashed onto the MikroE clicker.
