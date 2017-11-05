# homeassistant-config
These are [my](https://twitter.com/allanak) personal [Home Assistant](https://home-assistant.io/) configuration files. Feel free to learn from my mistakes :)

## Build Status (Travis-CI)
[![Build Status](https://travis-ci.org/allanak/homeassistant-config.svg?branch=master)](https://travis-ci.org/allanak/homeassistant-config)

## Current Configuration
* Raspberry Pi 3 Model B using [Hass.io](https://home-assistant.io/hassio/)

##### Fair warning: I've been in the process of migrating from Samsung SmartThings to Home Assistant. While much of this works, it is constantly under construction :)

#### Automations
### Lights
* Turn on kitchen lights when motion detected and off when motion stops (motion_kitchen_lights.yaml)
* Turn on garage lights when door is opened and off shortly after it closes (garage_lights.yaml)
### Convenience
* Start casting a music stream when I walk into the bathroom in the morning (morning_routine.yaml)
* Remind me to take out the trash if tomorrow is garbage collection day when entering the kitchen (morning_routine.yaml)
* Set my AV receiver to the proper input if its in my Google Cast group if I'm not already watching TV (chromecast.yaml)
* Send washer/dryer finished notifications based on energy meters and announce completion via Google Home (laundry_notifications.yaml)
* Wake me up at the specified time using transitioned lighting (alarm_clock.yaml)
* If it's a travel day per my TripIt calendar, remind me where I'm going after I leave the bathroom in the morning
* Hot Tub control (Balboa Wi-Fi) and temperature readings
### Security
* Arm alarm when Night mode kicks in (alarm.yaml)
* Arm alarm when house is empty for a while (alarm.yaml)
* Turn on/off perimeter lighting after sunset/sunrise (night_lighting.yaml)
* Turn on/off evening lighting at night, off at midnight (night_lighting.yaml)
### UI Enhancements/Customizations
* Hide media players when their state is idle/off (hide_mediaplayers.yaml)
* Set theme based on sunrise/sunset (hass_theme.yaml)
* Use [Custom UI elements](https://github.com/andrey-git/home-assistant-custom-ui) for tweaking UI objects
### Housekeeping
* Send a notification if my SSL certificate is going to expire in <10 days (hass_tasks.yaml)
* Send a notification when an update is available for Home Assistant (hass_tasks.yaml)
* Send a notification upon failed login attempts (hass_tasks.yaml)

#### Devices
* GE Z-Wave Switches and Dimmers
* [Aeon Labs DSC06106 Z-Wave Smart Energy Switch](https://www.amazon.com/Aeon-Labs-DSC06106-ZWUS-Z-Wave-Energy/dp/B007UZH7B8)
* [Ring Pro Doorbell](https://ring.com/video-doorbell-pro)
* [Logitech Harmony Hubs](https://www.logitech.com/en-us/product/harmony-hub)
* [Broadlink RM Pro](https://www.amazon.com/Broadlink-Automation-Universal-Compatible-Smartphones/dp/B01GIXZDKO)
* Hikvision IP Cameras and NVR
* Google Chromecast Audio, Video and Google Homes using [Google Assistant](https://home-assistant.io/components/google_assistant/) 
* Amazon Echo and Echo Dots (using [haaska](https://github.com/auchter/haaska))
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

### Screenshots
![Default View](https://github.com/allanak/homeassistant-config/blob/master/images/default.png?raw=true)
![Entertainment](https://github.com/allanak/homeassistant-config/blob/master/images/entertainment.png?raw=true)
![People](https://github.com/allanak/homeassistant-config/blob/master/images/people.png?raw=true)
![Security](https://github.com/allanak/homeassistant-config/blob/master/images/security.png?raw=true)
![Outdoor](https://github.com/allanak/homeassistant-config/blob/master/images/outdoor.png?raw=true)
![Events](https://github.com/allanak/homeassistant-config/blob/master/images/events.png?raw=true)

### Thanks to many example configs that helped immensely! Specifically [arsaboo](https://github.com/arsaboo/homeassistant-config/) and [stanvx](https://github.com/stanvx/Home-Assistant-Configuration) and [oakbrad](https://github.com/oakbrad/brad-homeassistant-config)
