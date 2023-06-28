# Air Quality Probe
![Front](/pictures/case_front.jpg)
This DIY Air Quality Sensor measures temperature, humidity, pressure, air quality (IAQ), CO2 and VOC.
The data is visualy represented on a display as well available via [Home Assistant](https://www.home-assistant.io).

# Where to find what?
## case
Here are files related to the housing for the DIY probe. The housing is optimized for 3d printing.
## electronics
Here you find schematics, pcb desings and BOM files.
## firmware
Please visit https://hardware.iaims.biz to flash the firmware.
Code can be found in https://github.com/maikischa/airquality-probe-firmware
## pictures
Example pictures of the probe

# How to install?
You can install the firmware via your own esphome installation or on https://hardware.iaims.biz

# Hardware
## Air Quality Probe
This project uses the [Bosch BME 680](https://www.bosch-sensortec.com/products/environmental-sensors/gas-sensors/bme680/) to meassure the airqulity. The housing is designed to hold a [jOY-iT BME 680](https://www.joy-it.net/de/products/SEN-BME680) sensor board.
## Display
I used an ILI9341 TFT LCD Screen. Have a look at [aliexpress](https://www.aliexpress.com/af/Ili9341.html)
## Mainboard
![PCB_V0.2](pictures/pcb_v0.1.png)
This project uses a custom PCB based on an[ ESP32-WROOM-32E](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32e_esp32-wroom-32ue_datasheet_en.pdf). All connectors are placed in a way that it fits nicely in the housing.


# Author
I designed this project to measure the air quality in my home. I would be happy if someone finds this project usefull and maybe helps me to imporve the project. Feel free to fork, commit or whatever you want to do with this project.
