# VL6180X Arduino library modifed for software I2C.


This is a fork of the [Pololu VL6180X driver](https://www.pololu.com/product/2489)


## Changes from the Pololu library

This library works with the SoftwareWire I2C library instead of the Wire library. This allows you to use any arduino digital pins instead of the SDA and SDL pins. Download the SoftwareWire library from https://github.com/Fire7/SoftwareWire 

