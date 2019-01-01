![Logo](admin/solarlog.png)
# ioBroker.solarlog

[![NPM version](http://img.shields.io/npm/v/iobroker.solarlog.svg)](https://www.npmjs.com/package/iobroker.solarlog)
[![Downloads](https://img.shields.io/npm/dm/iobroker.solarlog.svg)](https://www.npmjs.com/package/iobroker.solarlog)

[![NPM](https://nodei.co/npm/iobroker.solarlog.png?downloads=true)](https://nodei.co/npm/iobroker.solarlog/)

An ioBroker adapter for solarlog - devices

The open JSON-interface (offene Json-Schnittstelle) has to be activated in the Solarlog's configuration menue (Konfiguration - System - Zugangskontrolle - Offene Json-Schnittstelle: aktivieren.)

Install adapter, create instance.
Set Solarlog - IP-adress and polling - intervall 

Check if all inverter - data is collectet. !! The user-password in solarlog has to be deactivated for this option!!
Achtung: Damit die Abfrage der Unterz�hler funktioniert, muss das Benutzerpasswort im Solarlog deaktiviert sein

Tested on:
Solarlog 200PM+ / 300PM+ / 500 / 1200Meter


## Changelog
### 0.0.9
- another bugfix daysum - function
### 0.0.8
- bugfix daysum - function
### 0.0.7
- import of daily sum of production/consumption per inverter/meter in Wh
- info connection state fixed
### 0.0.6
- optimized evaluation of number of inverters/meters to import

### 0.0.5
- better readme
- correct labes in config-dialogue

Planned for next version: reading solarlog smart energy settings and states

### 0.0.4
- Inverter-import optional
- Error - logs refer to functions
- better readme

Planned for next version: reading solarlog smart energy settings and states

### 0.0.3
New functions added!
- reads all defined inverters/meters 
- sets objects named as in solarlog 
- gets values (current production/consumption) and states for each inverter

Planned for next version: reading solarlog smart energy settings and states

### 0.0.2 First running version

Defined objects: 
- Time last data sync
- Installed generator power
- Total output PAC from all of the inverters and meters in inverter mode.
- Total output PAC from all of the inverters 
- Average voltage UAC from the inverter
- Average voltage UDC from the inverter
- Total yield for the day from all of the inverters
- Total yield for the previous day from all of the inverters
- Total yield for the month from all of the inverters
- Total yield for the year from all of the inverters
- Total yield from all of the inverters
- Current total consumption PAC from all of the consumption meters
- Total consumption from all of the consumption meters
- Total consumption for the previous day; all of the consumption meters
- Total consumption for the month; all of the consumption meters
- Total consumption for the year; all of the consumption meters
- Accumulated total consumption, all Consumption meter

Planned Objects:
- Description/Yield/Consuption of all connected inverters and meters


## License
The MIT License (MIT)

Copyright (c) 2018 forelleblau marceladam@gmx.ch

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
