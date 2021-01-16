# CampusMap

[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

IoT-driven predictive insight into weather, foot traffic, noise levels, and more across UofT St. George campus.

## Focus

Give insight into UofT campus activity. For example:

- Busyness (noise level & camera movement)
- Study Space Density (bluetooth/MAC address device visibility)
- Weather (temperature, humidity, light, and air quality sensors)
- And more!

## CampusMap Node

The IoT device itself. Based on the ESP32 microcontroller.

### Requirements

Microcontroller:
- Wi-Fi and Bluetooth connectivity
- Camera support
- Low cost
- Popular; many open-source libraries available

Sensors and Power:
- Lithium polymer battery and charging unit
- Solar panel
- GPS for device location
- Camera
- Microphone
- Temperature sensor
- Humidity sensor
- Air quality sensor
- etc. sensors

## CampusMap.ca

The webapp that allows users to view a 'heat map' of various values.