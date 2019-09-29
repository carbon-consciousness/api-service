# api-service
flows.json contains all the NodeRed code used to in this MVP.
Flow's description:
Feed the DB:  Collect the data from the MQTT endpoint and fill the Cloudant DB on the IBM cloud.
Query the DB: We query the DB and based on the consumed electricity we calculate the CO2 footprint.
Demo_Data: Present the data collected as a REST API.
MQTT TEST: We grab all the MQTT topic.
Upload Image: In this flow we try to use the bite.ai API to understand which food has been coocked and the CO2 footprint.
Demo2_Data: This flow provide demo data not available in the realtime MQTT data flow.
