# FakeSensorDataAPI
This repo is just basically there to provide some fake sensor data using [json-sever](https://github.com/typicode/json-server) for the **Dataskop** project.
The format of the 20 entries is the following:

```json
{
  "dev_eui": "1Lqw2rBqDvHYbxMNNTabDuYKhY9VTcgJSL",
  "time": "2020-07-17T08:21:14Z",
  "digitalHallSensor_state": false,
  "analogHallSensor_mVolt": 1156,
  "batteryLevel_mVolt": 1178,
  "bagEmpty": true,
  "batteryLevel": 15.0,
  "location": "building north"
},
```
The data is generated randomly using [Mockaroo](https://www.mockaroo.com/). 

## API Endpoint
**Description**: Its possible to use GET, POST, PUT, PATCH and DELETE. Changes aren't persisted between calls.

**Info**: The online endpoint only allows 10KB for free thats why only 20 entries are included in the `db.json`.

**URL**: https://my-json-server.typicode.com/doomsayer2/FakeSensorDataAPI/sensors 
