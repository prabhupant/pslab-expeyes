# Pocket-Science-Lab
This repository hosts the programs for additional experiments and sensor plugins for ExpEYES. 

[![Build Status](https://travis-ci.org/fossasia/Pocket-Science-Lab.svg?branch=master)](https://travis-ci.org/fossasia/Pocket-Science-Lab)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/18fad6e7f96a49fe8ec531ad40149664)](https://www.codacy.com/app/mb/Pocket-Science-Lab?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=fossasia/Pocket-Science-Lab&amp;utm_campaign=Badge_Grade)
[![Gitter](https://badges.gitter.im/fossasia/pslab.svg)](https://gitter.im/fossasia/pslab?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

## Installation

#### 1. Install ExpEYES
You can install ExpEYES easily on any Linux machine. There are deb files available that we included in the repository. Please find details how to [install ExpEYES in the Readme.md](/ExpEYES/Readme.md).

### 2. Steps to install experiments

The software extension that are available in this repository in the folder /experiments can be installed as follows:
* Copy the programs in home folder

  ####ToDo : 
  Create makefile for installing programs in ExpEYEs directory and make these experiments available in a dropdown menu of main GUI.

### 3. How to run experiments

For Experiments various sensors and experimental setups are required. Typical steps are:
* Connect ExpEYES to your PC/Laptop
* Run Expeyes from Education Menue. The main ExpEYES GUI will popup. Check whether the device is detected.
* Then close the ExpEYES GUI.
* Open the terminal and run the program for e.g.

 `~ $ python coupledpendulum.py`


### 4. How to collect and save data

In order to make the experiments useful you need to collect and save data.
* Please describe here how to collect data and to save and use it (TO DO)


## Sensors and Devices

Please check out our list of supported devices:

1. Accelerometer:
* Sensor Used: ADXL 335 - Three axis
2. Magnetic Field Sensor
* Sensors Used:   KY 003, 3144 Hall Effect Sensor
3. Infra-red Object Sensor
* Sensor Used: Locally Made using IC LM-358N
4. Ultrasonic Position Sensor
* Sensor Used:    SRF-05 HY, SRF-04
5. Temperature Sensor
*  Sensor Used: PT-100 and LM-35
6. Humidity Sensor
* Sensor Used: DHT-11, HS-1101
7. Pressure- Barometric 
* Sensor Used: BMP180 Digital sensor
8. Pressure
* Sensor Used: Pizzo Electric sensor
9. Gas Sensors - Sensor Used:
* MQ-4 for Methane
* MQ-6 for LPG
* MQ-7 for Carbon Monoxide
10. Colour Sensor ( in progress)
* Sensor Used: IC-TCS3200D-SOP8
11. Anemometer- Wind Speed
* Sensor Used: Home-made 
12. Wind Direction
* Sensor Used: Home-made
13. Rotatory Motion Sensor
* Sensor Used: DC Motor and a pick-up coil
14. Motion Sensor-Photo Gate
* Sensor Used: Photo Gate using Photo Diode
15. Other devices used as sensors
* Solar Cells
* Induction coil
* condensor mic
* ATTINY-85 MCU used for sine wave generation
* Raspberry Pi 2 Model B for stand-alone weather station
* MicroHope

## Web Connectors

It is possible to collect data and publish it automatically on the web on your own web application or on social networks like Twitter and Facebook. Find more info [web connectors here](/web-connectors/Readme.md).

### Blog posts related to ExpEYES on FOSSASIA blog 
* [Sensor Plugins for ExpEYES](http://blog.fossasia.org/low-cost-laboratory-everyone-sensor-plug-ins-expeyes-measure-temperature-pressure-humidity-wind/)
