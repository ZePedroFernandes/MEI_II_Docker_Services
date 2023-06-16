# ! Windows Only !

# Docker Services for iIndustry
- Node red
- Eclipse Mosquitto
- CrateDB
- Grafana
- Postgres for odoo
- Odoo

## Node Red
### Links
- Main app - http://localhost:1880
- Dashboards - http://localhost:1880/ui
 
## Mosquitto
Listen to a Mosquito topic via cmd  
Download site: https://mosquitto.org/download/  
Install folder: C:\Program Files\mosquitto  
Add the install folder to the PATH environment variable

```bash
mosquitto_sub -h localhost -t "sensor/temperature"
```

Publish into a Mosquito topic via cmd

```bash
mosquitto_pub -h localhost -t sensor/temperature -m 23
```

## CrateDB
- App - http://localhost:4200
- Connect to Node Red - https://flows.nodered.org/node/node-red-contrib-crate


## Grafana
- Get started https://grafana.com/docs/grafana/latest/getting-started/build-first-dashboard/

## Odoo
- Main app - http://localhost:8069/