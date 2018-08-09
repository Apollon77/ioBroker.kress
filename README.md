[![Kress-Robotics](admin/kress-2.png)](https://www.kress-robotik.com/de/)

Bild-Quelle: https://www.kress-robotik.com/de/

ioBroker.kress
=============
 
[![NPM version](http://img.shields.io/npm/v/iobroker.kress.svg)](https://www.npmjs.com/package/iobroker.kress)
[![Downloads](https://img.shields.io/npm/dm/iobroker.kress.svg)](https://www.npmjs.com/package/iobroker.kress)

[![NPM](https://nodei.co/npm/iobroker.kress.png?downloads=true)](https://nodei.co/npm/iobroker.kress/)

**Tests:** Linux/Mac: [![Travis-CI](https://api.travis-ci.org/MeisterTR/ioBroker.kress.svg?branch=master)](https://travis-ci.org/MeisterTR/ioBroker.kress)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/MeisterTR/ioBroker.kress?branch=master&svg=true)](https://ci.appveyor.com/project/MeisterTR/ioBroker-kress/)


[Deutsche Beschreibung hier](README_de.md)

This adapter connects IoBroker with your Kress cloud support
Temperatures, mowing times, battery level and various other data are read out from the mower
The adapter can control the mower and you can change config params like mowtimes.

## installation
At least Node 4.X.X must be installed, Node 0.10 and 0.12 are no longer supported by this adapter.

## settings
- to connect to the mower type in email and password from your worx account in the Config.


## second mower
-If two mowers are to be integrated, a second instance must be installed, one is selected in the Config mower 0 and in the second mower 1 and so on.

## Changelog
#### 2.5.5 (17.07.2018)
* (MeisterTR) initinal relase
 
## License
The MIT License (MIT)

Copyright (c) 2017 MeisterTR <meistertr.smarthome@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
