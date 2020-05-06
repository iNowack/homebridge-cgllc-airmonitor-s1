# homebridge-cgllc-airmonitor-s1


## Instalation

1. Install required package: `npm install -g homebridge-cgllc-airmonitor-s1`

## Configuration
```json
"accessories": [
        {
            "accessory": "ClearGrassAirMonitor",
            "name": "Office Air Monitor",
            "ip": "xxx.xxx.xxx.xxx",
            "token": "--------",
            "showTemperature": true,
            "showHumidity": true,
            "showAirQuality": true,
            "showCo2": true,
            "co2_Threshold": 1000,
            "tVoc_Adjust": 1000            
        }
    ]
```

## Settings

1. tVoc_Adjust : change tvoc value (0.100 --> 100)
                homekit display 0.100 to 0

## Minimal configuration

