# homeassistant-config
These are [my](https://twitter.com/allanak) personal Home Assistant (https://home-assistant.io/) configuration files. Feel free to learn from my mistakes :)

## Build Status (Travis-CI)
[![Build Status](https://travis-ci.org/allanak/homeassistant-config.svg?branch=master)](https://travis-ci.org/allanak/homeassistant-config)

## Current Configuration
* Raspberry Pi using [Hass.io](https://home-assistant.io/hassio/)

##### Fair warning: I've been in the process of migrating from Samsung SmartThings to Home Assistant. While much of this works, it is constantly under construction :)

#### Automations
### Lights
* Turn on kitchen lights when motion detected
* Turn on garage lights when door is opened
### Convenience/Security
* Start casting a music stream when I walk into the bathroom in the morning
* Send washer/dryer finished notifications based on energy meters
* Arm alarm at midnight when home
* Arm alarm when house is vacated for a while
* Turn on/off perimeter lighting after sunset/sunrise
* Turn on/off evening lighting at night, off at midnight
### UI Enhancements
* Hide media players when their state is idle/off
* Set theme based on sunrise/sunset
* Various iOS context notifications for conditions such as camera activity
### Housekeeping
* Send a notification when my SSL certificate is going to expire in <10 days
* Send a notification upon failed logins
* Send a notification when an update is available for Home Assistant

#### Devices
* GE Z-Wave Switches and Dimmers
* [Aeon Labs DSC06106 Z-Wave Smart Energy Switch](https://www.amazon.com/Aeon-Labs-DSC06106-ZWUS-Z-Wave-Energy/dp/B007UZH7B8)
* [Ring Pro Doorbell](https://ring.com/video-doorbell-pro)
* [Logitech Harmony Hubs](https://www.logitech.com/en-us/product/harmony-hub)
* [Broadlink RM Pro](https://www.amazon.com/Broadlink-Automation-Universal-Compatible-Smartphones/dp/B01GIXZDKO)
* Hikvision IP Cameras and NVR
* Google Chromecast Audio, Video and Google Homes
* Amazon Echo and Echo Dots
* Android TV ([NVidia Shield](https://www.nvidia.com/en-us/shield/))
* [Schlage Connect Z-Wave Locks](https://www.amazon.com/Schlage-Connect-Touchscreen-Deadbolt-Technology/dp/B01AGX7K12)
* [Ecobee3 Smart Thermostats](https://www.amazon.com/ecobee3-Thermostat-Sensor-Generation-Amazon/dp/B00ZIRV39M)
* [Linear GD00Z-4 Garage Door Controller](https://www.amazon.com/GoControl-Linear-GD00Z-4-Z-Wave-Controller/dp/B00M75TEIU) (Not working with OpenZWave 1.4)
* Osram Lightify Zigbee Gateway
* [Osram Lightify Gardenspot RGB](https://www.amazon.com/SYLVANIA-Smart-Landscape-Lighting-Gardenspots/dp/B00R1PB2ZY)
* [Osram Lightify Flex RGBW](https://www.amazon.com/SYLVANIA-Smart-Connected-Tunable-Daylight/dp/B00R1PB80I)
* Osram Lightify RGBW A19 Bulbs
* [Ubiquiti UAP-AC-LR Wireless Access Point](https://www.amazon.com/Ubiquiti-UAP-AC-LR-Networks-Enterprise-System/dp/B015PRCBBI)
* [Aeon Z Stick Gen 5](https://www.amazon.com/Aeotec-Z-Stick-Z-Wave-create-gateway/dp/B00X0AWA6E)
* Raspberry Pi 3 running hass.io
* SanDisk 64GB MicroSD Card

### Sensors
* [Envisalink EVL-4](https://www.amazon.com/Envisalink-EVL-4EZR-Security-Interface-Honeywell/dp/B016WQTJ4S) connected to DSC PC-1832 Alarm
* [Monoprice Z-Wave PIR Motion Sensors](https://www.monoprice.com/product?p_id=15271)
* Z-Wave Door Sensors
* [FirstAlert Z-Wave Smoke Detectors](https://www.lowes.com/pd/First-Alert-Z-Wave-Battery-powered-3-Volt-Photoelectric-Sensor-Smoke-Detector/4780111)
* Xiaomi Aqara Water Leak Sensors (Zigbee, still need to integrate)
* [Plex](https://www.plex.tv/) for Plex server activity
* [NZBGet](https://nzbget.net/) for usenet download activity
* [Sonarr](https://sonarr.tv/) for TV show activity
* [Radarr](https://radarr.video/) for movie activity
* [Travis-CI](https://travis-ci.org/) Sensor
* [USPS Mail Sensor](https://home-assistant.io/components/sensor.usps/)
* [UPS Package Sensor](https://home-assistant.io/components/sensor.ups/)
* [FedEx Package Sensor](https://home-assistant.io/components/sensor.fedex/)


### Thanks to many example configs that helped immensely! Specifically [arsaboo](https://github.com/arsaboo/homeassistant-config/) and [stanvx](https://github.com/stanvx/Home-Assistant-Configuration) and [oakbrad](https://github.com/oakbrad/brad-homeassistant-config)
