============
FTDI Toolkit
============

Copyright (c) 2018-2022 `Antmicro <https://www.antmicro.com>`_

.. figure:: img/antmicro-ftdi-toolkit.jpg

Overview
--------

This repository contains open hardware design files for an experimental adapter board based on FTDI FT2232H IC.
The board exposes the programmable IO buses from the FT2232H on a 2.54 mm goldpin header, allowing the implementation of many popular IO interfaces which are useful during hardware debugging.
Those interfaces include:

* UART - two independent channels with optional flow control and selectable IO voltage (5.0V, 3.3V, 1.8V) 
* I2C bus master with selectable IO voltage standard (5.0V, 3.3V, 1.8V)
* SPI bus master with selectable IO voltage standard (5.0V, 3.3V, 1.8V)
* JTAG (openocd-compliant with fixed 3.3V IO voltage standard)
* SWD (openocd-compliant with fixed 3.3V IO voltage standard)

The design files were prepared in KiCad.

Repository structure
--------------------
The main repository directory contains KiCad PCB project files, a LICENSE and README.
The remaining files are stored in the following directories:

* ``lib`` - contains the component libraries
* ``img`` - contains graphics for this README

License
=======

`Apache-2.0 <LICENSE>`_
