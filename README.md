# bmp180

Golang package for interfacing with BMP180 environmental sensor.

[![Build Status](https://travis-ci.org/michaelfranzl/bmp180.svg?branch=master)](https://travis-ci.org/michaelfranzl/bmp180)

Package `bmp180` provides an interface to the BMP180 family of environmental (temperature, pressure) sensors attached to an I2C interface.

Package `stub` provides an emulated BMP180 device that can be used to test functionality of the `bmp180` package when no I2C bus or physical device is attached or available.

Pressure and temperature calculations are based on a paper called ["Bosch BMP085 Barometer Floating Point Pressure Calculations"](http://www.osengr.org/WxShield/Downloads/BMP085-Calcs.pdf).

See `bmp180_test.go` for a working example.

Copyright 2017 Michael Franzl. All rights reserved.

Use of this source code is governed by a BSD-style license that can be found in the LICENSE file.
