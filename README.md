# homebridge-NinjaBlock-Temperature
[NinjaBlock](https://developers.ninja/legacy/index.html) plugin for [HomeBridge](https://github.com/nfarina/homebridge)

# Installation


1. Install homebridge using: npm install -g homebridge
2. Install this plugin using: npm install -g homebridge-NinjaBlock-Temperature
3. Update your configuration file. See sample-config.json snippet below. 

# Configuration

Configuration sample:

 ```
 {
"accessory": "NinjaBlock-Temperature",
"temperature_url" : "<YOUR URL GOES HERE>",
"service" : "Temperature Sensor",
"name" : "NinjaBlock Temp"
 }
```

Fields: 
* "accessory": Must always be "NinjaBlock-Temperature" (required)
* "temperature_url": Get the API Endpoint URL from the NinjaBlocks Dashboard, add "?user_access_token=" and add your [API Access Token](https://a.ninja.is/hacking).
*   Example: https://a.ninja.is/rest/v0/device/4412BB000300_0101_0_31?user_access_token=abc123"
* "service": Must always be "Temperature Sensor" (required)
* "name": Can be anything but is required
