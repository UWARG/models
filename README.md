# Models

This repository contains the model configurations for WARG's various aircraft. This includes radio and flight controller configurations where appropriate.


This repository is broken down into two main directories:
- **radios**: Contains configurations for radios, such as calibrations, global functions, etc.
- **aircraft**: Contains configurations for flight controllers and radio models, as appropriate


### Radios

Most of our radios use EdgeTx or OpenTx. These are the firmwares that run on the radio. You can configure your radio settings on the radio itself, or you can use EdgeTx/OpenTx Companion. This software allows you to backup and copy settings, as well as make changes to the radio easily.

### Aircraft

This directory contains configurations for flight controllers and aircraft models (that live on the radio). 

It is recomended that EdgeTx Companion is used to back up models from the radio.

Firmware configurations will be specific to the flight software used. In the case of ardupilot, you will need to save the parameters list from your preferred GCS (e.g. Mission Planner). In the case of ZeroPilot, refer to the ZP3-SW documentation.