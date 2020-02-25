# b5w-d6f-d6t-2jcieev01-arduino
It is a sample projects for OMRON sensor (Light convergent sensor, air quality sensor, flow sensor, differential pressure sensor, thermal sensor) with evaluation kit **2JCIE-EV01-AR1**, **2JCIE-EV01-FT1**
and some Arduino boards.


## B5W-LB: Light Convergent Reflective Sensor
Reliable Detection of Shiny, Black or Transparent objects.


## B5W-LD: Air Quality Sensor
Highly Sensitive and Compact Air Quality Sensor.

## D6T: Termal Sensor
High Sensitivity Enables Detection of Stationary Human Presence.

## D6F: Flow Sensor
Can Measure Low-flow rate and High Accuracy with Superior Resistance to Environments.

## D6F-PH: Differential Pressure Sensor
A Compact, High-accuracy Differential Pressure Sensor with Superior Resistance to Environments.

## Description
this Arduino sample projects for acquiring data from sensors on 2JCIE-EV01.
sample projects output the sensor data to USB-Serial ports.

| example    | description                     | board |
|:----------:|:--------------------------------|:-----------------------|
| b5w-ld0101 | All sensor              | Arduino MKR-WiFi1010/ Adafruit Feather ESP32 |


## DEMO
sample output from All sensor

```
13:42:26.053 -> 0.37  [V]     (B5W-LB)
13:42:26.053 -> 24.8 [degC]   (D6T-01)
13:42:26.053 -> -0.01 [Pa]     (D6F-PH)
13:42:26.053 -> 5.00 [L/min]  (D6F-10)
13:42:26.053 -> 1[count], ----[20s count]   (B5W-LD)
13:42:26.053 ->  
13:42:27.096 -> 1.20  [V]     (B5W-LB)
13:42:27.096 -> 22.8 [degC]   (D6T-01)
13:42:27.096 -> -0.01 [Pa]     (D6F-PH)
13:42:27.096 -> 5.00 [L/min]  (D6F-10)
13:42:27.096 -> 1[count], ----[20s count]   (B5W-LD)
13:42:27.096 ->  
13:42:28.107 -> 2.11  [V]     (B5W-LB)
13:42:28.107 -> 22.9 [degC]   (D6T-01)
13:42:28.107 -> -0.01 [Pa]     (D6F-PH)
13:42:28.107 -> 5.00 [L/min]  (D6F-10)
13:42:28.142 -> 1[count], 19[20s count]   (B5W-LD)
13:42:28.142 -> 

```


## Installation
see `https://www.arduino.cc/en/guide/libraries`

### Install from Arduino IDE
1. download .zip from this repo [releases](releases)
    or [master](archive/master.zip) .
2. Import the zip from Arduino IDE
3. Then, you can see the samples in `File >> Examples` menu.
4. Select examples for your favorite sensors, build and program to boards.

### Manual install
1. download this repo

    ```shell
    $ git clone https://github.com/hankha/b5w-d6f-d6t-2jcieev01-arduino
    ```

2. launch Arduino-IDE and select our sketch to load.
3. build and program to boards.


## Dependencies
None


## Links
- [Arduino samples for 2JCIE-01-AR1/FT1](https://github.com/omron-devhub/2jcieev01-arduino)
- [RaspberryPi samples for 2JCIE-01-RP1](https://github.com/omron-devhub/2jcieev01-raspberrypi)
- [Arduino sample for D6T on 2JCIE-01-AR1/FT1](https://github.com/omron-devhub/d6t-2jcieev01-arduino)
- [RaspberryPi sample for D6T on 2JCIE-01-RP1](https://github.com/omron-devhub/d6t-2jcieev01-raspberrypi)
- [Arduino sample for D6F on 2JCIE-01-AR1/FT1](https://github.com/omron-devhub/d6f-2jcieev01-arduino)
- [RaspberryPi sample for D6F on 2JCIE-01-RP1](https://github.com/omron-devhub/d6f-2jcieev01-raspberrypi)


## Licence
Copyright (c) OMRON Corporation. All rights reserved.

Licensed under the MIT License.
