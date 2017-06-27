temperature
===========

_temperature_ is a temperature and humidity data collection system.

## Requirements

* Any Arduino board
* A DHT11 (or DHT22) temperature-humidity sensor
* Any ESP8266 microcontroller
* Any LCD based on the Hitachi HD44780 chipset (optional)
* Node.js, npm `>= 7.10.0`, `>= 4.2.0`
* MySQL `>= 5.7.18`
* Docker, docker-compose `>= 17.03.1`, `>= 1.11.2` (optional)

## Usage

1. Compile and upload the sensor [program](https://github.com/toksaitov/temperature-sensor) to Arduino.
2. Compile and upload the beacon [program](https://github.com/toksaitov/temperature-beacon) to ESP8266.
3. Connect and configure the Serial interface between two devices.
4. Deploy the data collection back end [server](https://github.com/toksaitov/temperature-back).

## Credits

*temperature* was created by [Dmitrii Toksaitov](https://github.com/toksaitov).

