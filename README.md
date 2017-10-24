# homeassistant-config
These are [my](https://twitter.com/allanak) personal Home Assistant (https://home-assistant.io/) configuration files. Feel free to learn from my mistakes :)

## Build Status (Travis-CI)
[![Build Status](https://travis-ci.org/allanak/homeassistant-config.svg?branch=master)](https://travis-ci.org/allanak/homeassistant-config)

## Current Configuration
* Raspberry Pi using [Hass.io](https://home-assistant.io/hassio/)

##### Fair warning: I've been in the process of migrating from Samsung SmartThings to Home Assistant, so some of this may not fully work yet and a lot of this is a work in progress.

#### Automations
* Turn on kitchen lights when motion detected
* Turn on garage lights when door is opened
* Start casting a music stream when I walk into the bathroom in the morning
* Arm alarm at midnight when home
* Arm alarm when house is vacated for a while
* Hide media players when their state is idle/off
* Set theme based on sunrise/sunset
* Various iOS context notifications for conditions such as camera activity
* Send a notification when my SSL certificate is going to expire in <10 days
* Send a notification upon failed logins
* Send a notification when an update is available for Home Assistant

#### Devices
* GE Z-Wave Switches and Dimmers
* Ring Pro Doorbell
* Logitech Harmony Hubs
* [Broadlink RM Pro](https://www.amazon.com/Broadlink-Automation-Universal-Compatible-Smartphones/dp/B01GIXZDKO)
* Hikvision IP Cameras and NVR
* Google Chromecast Audio, Video and Google Homes
* Amazon Echo and Echo Dots
* Android TV (NVidia Shield)
* [Schlage Connect Z-Wave Locks](https://www.amazon.com/Schlage-Connect-Touchscreen-Deadbolt-Technology/dp/B01AGX7K12)
* [Ecobee3 Smart Thermostats](https://www.amazon.com/ecobee3-Thermostat-Sensor-Generation-Amazon/dp/B00ZIRV39M)
* [Linear GD00Z-4 Garage Door Controller (Not working with OpenZWave 1.4)](https://www.amazon.com/GoControl-Linear-GD00Z-4-Z-Wave-Controller/dp/B00M75TEIU)
* Osram Lightify Zigbee Gateway
* [Osram Lightify Flex RGBW](https://www.amazon.com/SYLVANIA-Smart-Connected-Tunable-Daylight/dp/B00R1PB80I)
* Osram Lightify RGBW A19 Bulbs
* [Osram Lightify Gardenspot RGB](https://www.amazon.com/SYLVANIA-Smart-Landscape-Lighting-Gardenspots/dp/B00R1PB2ZY)
* [Ubiquiti UAP-AC-LR Wireless Access Point](https://www.amazon.com/Ubiquiti-UAP-AC-LR-Networks-Enterprise-System/dp/B015PRCBBI)
* [Aeon Z Stick Gen 5](https://www.amazon.com/Aeotec-Z-Stick-Z-Wave-create-gateway/dp/B00X0AWA6E)
* Raspberry Pi 3 running hass.io
* SanDisk 64GB MicroSD Card

### Sensors
* [Envisalink EVL-4 connected to DSC PC-1832 Alarm](https://www.amazon.com/Envisalink-EVL-4EZR-Security-Interface-Honeywell/dp/B016WQTJ4S)
* [Monoprice Z-Wave PIR Motion Sensors](https://www.monoprice.com/product?p_id=15271)
* Z-Wave Door Sensors
* [FirstAlert Z-Wave Smoke Detectors](https://www.lowes.com/pd/First-Alert-Z-Wave-Battery-powered-3-Volt-Photoelectric-Sensor-Smoke-Detector/4780111)
* Xiaomi Aqara Water Leak Sensors (Zigbee, still need to integrate)
* [Plex for Plex server activity](https://home-assistant.io/components/sensor.plex/)
* [NZBGet for usenet download activity](https://home-assistant.io/components/sensor.nzbget/)
* [Sonarr for TV show activity](https://home-assistant.io/components/sensor.sonarr/)
* [Radarr for movie activity](https://home-assistant.io/components/sensor.radarr/)
* [Travis-CI Sensor(https://home-assistant.io/components/sensor.travisci/)
* [USPS Mail Sensor](https://home-assistant.io/components/sensor.usps/)
* [UPS Package Sensor](https://home-assistant.io/components/sensor.ups/)
* [FedEx Package Sensor](https://home-assistant.io/components/sensor.fedex/)
