# Docker Services for iIndustry
- Node red
- Eclipse Mosquitto
- CrateDB

## Node Red
### Links
- http://localhost:1880 - Main app
- http://localhost:1880/ui - Dashboards
 
## Mosquitto
Listen to a Mosquito topic via cmd

```bash
mosquitto_sub -h localhost -t "sensor/temperature"
```

Publish into a Mosquito topic via cmd

```bash
mosquitto_pub -h localhost -t sensor/temperature -m 23
```

## CrateDB
To connect go to http://localhost:4200