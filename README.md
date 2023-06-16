### Description
Getting started with Raspberry Pico, Adafruit BME280, and [Blues Wireless](https://blues.io/)

### Currently running
Currently running:
* `pico_sensor_notecard_A01.py`  _Notecarrier A, Notecard WBNA_

![current project](./images/pico_blues_bme680.png)

Development scripts
* `pico_blues_bme280_bme680.py`
* `pico_blues_bme280.py`

### Troubleshooting
* When all else fails, power cycle the Raspberry Pi Pico

### References Pico and BME280
* [How to Connect BME280 to Raspberry Pi Pico MicroPython](https://www.hackster.io/shilleh/how-to-connect-bme280-to-raspberry-pi-pico-micropython-91a392)
* [Library for bme280 package](https://github.com/SebastianRoll/mpy_bme280_esp8266)
    * [see also](https://github.com/robert-hh/BME280)
* [Source for an adapted Adafruit BME680 library that works with MicroPython](https://github.com/bsatrom/notecard-pico)
    * [see also](https://github.com/robert-hh/BME680-Micropython)
* [Troubleshooting error:  added address parameter](https://forums.raspberrypi.com/viewtopic.php?t=343123)
* [note-python: python library](https://github.com/blues/note-python)
* [dev.blues.io api](https://dev.blues.io/api-reference/notecard-api/introduction/)
* These two are together:
    * [Adding Cellular to the raspberry Pico bme680](https://www.hackster.io/brandonsatrom/adding-cellular-to-the-raspberry-pi-pico-b8a4b6)
    * [code for bme680 and pico - github](https://github.com/bsatrom/notecard-pico)

### Blues Wireless Reference
* [Getting Started (useful intro video)](https://blues.io/blog/get-started-cellular-raspberry-pi-webinar/)
* [Notecarrier A and GPS](https://www.hackster.io/rob-lauer/sending-a-cellular-gps-tracker-around-the-world-literally-4b830c)
* [Quick Start: Notecard and Notecarrier](https://dev.blues.io/quickstart/notecard-quickstart/notecard-and-notecarrier-f/)
* [Transforming data](https://dev.blues.io/guides-and-tutorials/routing-data-to-cloud/general-http-https/)
* [Notecard Built-in time and location](https://dev.blues.io/notecard/notecard-walkthrough/time-and-location-requests/)
    * Enabling GPS periodic, only checks when motion has been detected.
    * In the request then, `"best_location_type":"gps"`
* [Creating Routes, Using webhook for testing](https://dev.blues.io/guides-and-tutorials/routing-data-to-cloud/general-http-https/#introduction)
* [SDK (python)](https://dev.blues.io/tools-and-sdks/firmware-libraries/python-library/)
* [Adding Cellular to the Raspberry Pi Pico with the Blues Wireless Notecard Video](https://www.youtube.com/watch?v=rxq9vc1sW_0)

### References
* [micropython docs](https://docs.micropython.org/en/latest/rp2/quickref.html)
* https://www.robmiles.com/journal/2021/9/27/pico-and-feather-what-are-the-differences
* https://dev.blues.io/notecard/notecard-walkthrough/time-and-location-requests/
* [Detecting USB/battery power](https://forums.raspberrypi.com/viewtopic.php?t=300676)