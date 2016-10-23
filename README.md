# BBC micro:bit C++ template for DAL version 1.4.x

This is a very simple template designed as a base for any microbit C/C++ application using an older version of the micro:bit DAL (1.4.x).

The reason to have a template for an older version of the DAL is mostly to test code targeting the same version as used by [MicroPython](https://github.com/bbcmicrobit/micropython/).

On the terminal run:

```
yt target bbc-microbit-classic-gcc
yt build
```

The built output is located in:

```
build/bbc-microbit-classic-gcc/src/microbit-dalv1-template-combined.hex
```
