# b5w-2jcieev01-arduino
It is a sample projects for OMRON **B5W** Light Convergent Reflective type
Sensor with evaluation kit **2JCIE-EV01-AR1**, **2JCIE-EV01-FT1**
and some Arduino boards.

## B5W-LB: Light Convergent Reflective Sensor
Light Convergent Reflective Type for Reduced Color and Material
SusceptibilityReliable Detection of Shiny, Black or Transparent objects

## B5W-LD: Air Quality Sensor


## Description
this Arduino sample projects for acquiring data from sensors on 2JCIE-EV01.
sample projects output the sensor data to USB-Serial ports.

| example    | description                     | baord |
|:----------:|:--------------------------------|:-----------------------|
| b5w-ld0101 | Air Quality sensor              | Arduino MKR-WiFi1010/ Adafruit Feather ESP32 |
| b5w-lb2101 | Light convergent reflective type sensor | Arduino MKR-WiFi1010/ Adafruit Feather ESP32 |

## DEMO
sample output for B5W-LD0101

```
out1: 111[count], ----[count], out2: 0[count], ----[count]
out1: 111[count], ----[count], out2: 0[count], ----[count]
out1: 111[count], ----[count], out2: 0[count], ----[count]
out1: 111[count], ----[count], out2: 0[count], ----[count]
out1: 111[count], 1023[count], out2: 0[count], 0[count]
out1: 111[count], ----[count], out2: 0[count], ----[count]
out1: 111[count], ----[count], out2: 0[count], ----[count]
```

sample output for B5W-LB2101

```
B5W-LB: 0.12[mV]
B5W-LB: 0.00[mV]
B5W-LB: 0.00[mV]
B5W-LB: 3.21[mV]
```

## Installation
see `https://www.arduino.cc/en/guide/libraries`

### Install from Arduino IDE
1. download .zip from this repo [releases](releases)
    or [master](archive/master.zip) .
2. Import the zip from Arduino IDE

    ![install-ide-import-lib](https://user-images.githubusercontent.com/48547675/55043017-9a34e980-5077-11e9-885d-03f9f82e3491.JPG)

    ![install-select-zip](https://user-images.githubusercontent.com/48547675/55043034-a7ea6f00-5077-11e9-99d5-26423fb652b5.JPG)

3. Then, you can see the samples in `File >> Examples` menu.

    ![install-select-examples](https://user-images.githubusercontent.com/48547675/55043028-a28d2480-5077-11e9-8365-6745cda417ff.JPG)

4. Select examples for your favorite sensors, build and program to boards.

### Manual install
1. download this repo

    ```shell
    $ git clone https://github.com/omron-devhub/b5w-2jcieev01-arduino
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

