# USM 98 textures manager

[![CircleCI](https://circleci.com/gh/ecourtial/usm98-textures-manager/tree/master.svg?style=svg)](https://circleci.com/gh/ecourtial/usm98-textures-manager/tree/master) 
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/ecourtial/usm98-textures-manager/graphs/commit-activity) 
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/ecourtial/usm98-textures-manager) 
 [![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/ecourtial/usm98-textures-manager/blob/master/LICENSE)

## Description :notebook:

This small application is designed to help you to edit the textures in the game _Ultimate Soccer Manager 98_. It has been tested with USM98-99 (aka the USM98 2.0).

## Utilization

* If you just want to download and use the application, download it from [here](http://usm.dynamic-mess.com/downloads/tools/).
* For contributing, just fork the repo and clone your repo locally.

## Stack :light_rail:

* Build with Java Runtime Environment 1.8 (not tested with lower versions).
* Swing
* Maven
* JUnit

## Changelog 
### 1.0
* Feature to export and import adboards.
* Includes the color palette on CSV format.

### 1.1

#### New features
* Feature to import and export pitches (field).
* When converting from BMP to SPR: you can use a color override configuration for colors not recognized by the palette.
* Added a logger option to help modders to debug.

#### Bufixes
* Fix error output in the console.

#### Miscellaneous
* Trim entries when parsing the palette.