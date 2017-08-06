SlowSoftI2CMaster
================

Another Software I2C library, very similar to SoftI2CMaster, allowing you to use any Arduino pins for SDA and SCL.  The difference to the SoftI2CMaster library is that it is entirely written in C++, so you can use it also on ARM boards, such as Zero and Due. And you can use any pin on the ATMega256. As is stipulated by the title, it is definitely slower. On an UNO it runs with roughly 40kHz, on an ARM board with around 70 kHz. 

In principle, you could setup different I2C buses (as masters), but I do not see the point in it. In particular since you only could do I/O on one bus at a time.

As in the case of the SoftI2CMaster library, there exists a [wrapper library](https://github.com/felias-fogg/SlowSoftWire) that emulates the functionality of the Wire class.

This version of the library was forked from https://github.com/felias-fogg/SlowSoftI2CMaster and modified to work with the [Teensy 3.2](https://www.pjrc.com/store/teensy32.html).

This software is published under the [LGPL](http://www.gnu.org/licenses/lgpl-3.0.html)
