# homeassistant-config
These are [my](https://twitter.com/allanak) personal [Home Assistant](https://home-assistant.io/) configuration files. Feel free to learn from my mistakes :)

## Build Status (Travis-CI)
[![Build Status](https://travis-ci.org/allanak/homeassistant-config.svg?branch=master)](https://travis-ci.org/allanak/homeassistant-config)

## Current Configuration
* Raspberry Pi 3 Model B using [Hass.io](https://home-assistant.io/hassio/)

## Automations
### Lights
* Turn on kitchen lights when motion detected and off when motion stops (motion_kitchen_lights.yaml)
* Turn on garage lights when door is opened and off shortly after it closes (garage_lights.yaml)
* Turn off the downstairs lights when I start playing content at night on my NVidia Shield, dim them on when paused and back off when resumed (movie_time.yaml)
* Same as above for guest bedroom Chromecast
### Convenience
* Start casting a music stream when I walk into the bathroom in the morning (morning_routine.yaml)
* Remind me to take out the trash if tomorrow is garbage collection day when entering the kitchen (morning_routine.yaml)
* Set my AV receiver to the proper input if its in my Google Cast group if I'm not already watching TV (chromecast.yaml)
* Send washer/dryer finished notifications based on energy meters and announce completion via Google Home (laundry.yaml)
* Wake me up at the specified time using transitioned lighting (alarmclock.yaml)
* If it's a travel day per my TripIt calendar, remind me where I'm going after I leave the bathroom in the morning
* Hot Tub control (Balboa Wi-Fi) and temperature readings
### Security
* Arm alarm when Night mode kicks in, lock the doors and close the shades (alarm.yaml)
* Arm alarm when house is empty for a while (alarm.yaml)
* Turn on/off perimeter lighting after sunset/sunrise (night_lighting.yaml)
* Turn on/off evening lighting at night, off at midnight (night_lighting.yaml)
### UI Enhancements/Customizations
* Use meta device tracker python script to use most accurate source of presence (iOS app, OwnTracks and ping)
* Hide media players from the UI when their state is idle/off (hide_mediaplayers.yaml)
* Set theme based on sunrise/sunset (hass_theme.yaml)
* Use [Custom UI elements](https://github.com/andrey-git/home-assistant-custom-ui) for tweaking UI objects
### Housekeeping
* Send a notification if my SSL certificate is going to expire in <10 days (hass_tasks.yaml)
* Send a notification when an update is available for Home Assistant (hass_tasks.yaml)
* Send a notification upon failed login attempts (hass_tasks.yaml)

### Devices
* GE Z-Wave Switches and Dimmers
* [Aeon Labs DSC06106 Z-Wave Smart Energy Switch](https://www.amazon.com/Aeon-Labs-DSC06106-ZWUS-Z-Wave-Energy/dp/B007UZH7B8)
* [Ring Pro Doorbell](https://ring.com/video-doorbell-pro)
* LG OLED65C7P Smart TV
* Onkyo TX-NR636 Receiver
* Onkyo TX-NR676 Receiver
* [Logitech Harmony Hubs](https://www.logitech.com/en-us/product/harmony-hub)
* [Broadlink RM Pro](https://www.amazon.com/Broadlink-Automation-Universal-Compatible-Smartphones/dp/B01GIXZDKO)
* Xiaomi Gateway v2
* Xiaomi Roborock Smart Robot Vacuum Cleaner
* Somfy ZRTSI II
* Hikvision IP Cameras and NVR
* Google Chromecast Audio, Video and Google Homes using [Google Assistant](https://home-assistant.io/components/google_assistant/) 
* Amazon Echo and Echo Dots (using [haaska](https://github.com/auchter/haaska))
* Android TV ([NVidia Shield](https://www.nvidia.com/en-us/shield/))
* [Schlage Connect Z-Wave Locks](https://www.amazon.com/Schlage-Connect-Touchscreen-Deadbolt-Technology/dp/B01AGX7K12)
* [Ecobee3 Smart Thermostats](https://www.amazon.com/ecobee3-Thermostat-Sensor-Generation-Amazon/dp/B00ZIRV39M)
* [Linear GD00Z-4 Garage Door Controller](https://www.amazon.com/GoControl-Linear-GD00Z-4-Z-Wave-Controller/dp/B00M75TEIU) (Not working with OpenZWave 1.4)

### Lighting
* Philips Hue 2.1 Hub
* Philips Hue Lightstrip Plus
* Osram Lightify Zigbee Gateway
* [Osram Lightify Gardenspot RGB](https://www.amazon.com/SYLVANIA-Smart-Landscape-Lighting-Gardenspots/dp/B00R1PB2ZY)
* [Osram Lightify Flex RGBW](https://www.amazon.com/SYLVANIA-Smart-Connected-Tunable-Daylight/dp/B00R1PB80I)
* Osram Lightify RGBW A19 Bulbs

### Network Gear
* [Envisalink EVL-4](https://www.amazon.com/Envisalink-EVL-4EZR-Security-Interface-Honeywell/dp/B016WQTJ4S) connected to DSC PC-1832 Alarm
* [Ubiquiti UAP-AC-LR Wireless Access Point](https://www.amazon.com/Ubiquiti-UAP-AC-LR-Networks-Enterprise-System/dp/B015PRCBBI)
* [Aeon Z Stick Gen 5](https://www.amazon.com/Aeotec-Z-Stick-Z-Wave-create-gateway/dp/B00X0AWA6E)
* Raspberry Pi 3 running hass.io
* SanDisk 64GB MicroSD Card

### Sensors
* [Monoprice Z-Wave PIR Motion Sensors](https://www.monoprice.com/product?p_id=15271)
* Z-Wave Door Sensors
* [FirstAlert Z-Wave Smoke Detectors](https://www.lowes.com/pd/First-Alert-Z-Wave-Battery-powered-3-Volt-Photoelectric-Sensor-Smoke-Detector/4780111)
* Xiaomi Aqara Water Leak Sensors

### Third-party Integrations
* [Tautulli](http://tautulli.com/) for Plex server activity
* [NZBGet](https://nzbget.net/) for usenet download activity
* [Sonarr](https://sonarr.tv/) for TV show activity
* [Radarr](https://radarr.video/) for movie activity
* [Travis-CI](https://travis-ci.org/) Sensor for Github commits
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

#### Thanks to many example configs that helped immensely and the discord chat! Specifically [arsaboo](https://github.com/arsaboo/homeassistant-config/) and [stanvx](https://github.com/stanvx/Home-Assistant-Configuration) and [oakbrad](https://github.com/oakbrad/brad-homeassistant-config)
