| Field Type    | Name Attribute     | Unit  | Description                                   | Value | Type | Required | Example                      | Notes | Version |
|---------------|--------------------|-------|-----------------------------------------------|-------|------|----------|------------------------------|-------|---------|
| configuration | id                 |       | Reference id for measurement data node        |       |      | x        | <device id=“1“ type=“meteo“> |       | 2.0.1   |
| configuration | type               |       | device type                                   | meteo |      | x        | <device id=“1“ type=“meteo“> |       | 2.0.1   |
| configuration | uid                |       | device unique identifier                      |       |      | x        | <uid>MET12345</uid>          |       | 2.0.1   |
| configuration | name               |       | device name                                   |       |      |          | <name>Meteo A</name>         |       | 2.0.1   |
| configuration | serial             |       | device serial                                 |       |      |          | <serial>MET11.22.33</serial> |       | 2.0.1   |
| configuration | vendor             |       | device vendor                                 |       |      |          | <vendor>vendor 123</vendor>  |       | 2.0.1   |
| configuration | model              |       | device model                                  |       |      |          | <model></model>              |       | 2.0.1   |
| configuration | firmware           |       | device firmware                               |       |      |          | <firmware>1.23.3</firmware>  |       | 2.0.1   |
| datapoints    | SRAD[1..x]         | W/m²  | Irradiation sensors                           |       |      |          |                              |       | 2.0.1   |
| datapoints    | T[1..x]            | °C    | Temperature values                            |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_AH_ABS[1..x]     | g/m³  | Absolute humidity                             |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_AH_REL[1..x]     | %     | Relative humidity                             |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_ALT[1..x]        | m     | Local height                                  |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_AP_ABS[1..x]     | hPa   | Absolute air pressure                         |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_AP_REL[1..x]     | hPa   | Relative air pressure                         |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_AT[1..x]         | °C    | Air temperature                               |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_RF_ABS[1..x]     | mm    | Absolute precipitation                        |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_RF_I[1..x]       | mm/h  | Precipitation intensity                       |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_W_S[1..x]        | m/s   | Wind speed values                             |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_W_S[1..x]_MAX    | m/s   | Maximum wind speed values                     |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_W_D[1..x]        | °     | Wind direction values                         |       |      |          |                              |       | 2.0.1   |
| datapoints    | ERROR[1..x]        |       | Global meteo error conditions                 |       |      |          |                              |       | 2.0.1   |
| datapoints    | E_SNOW_DEPTH[1..x] | m     | Snow depth                                    |       |      |          |                              |       | 2.0.8   |
| datapoints    | E_F_S[1..x]        | rpm   | Fan speed                                     |       |      |          |                              |       | 2.0.8   |
| datapoints    | E_IH_REL[1..x]     | %     | Internal relative humidity                    |       |      |          |                              |       | 2.0.8   |
| datapoints    | E_IP_ABS[1..x]     | hPa   | Internal air pressure                         |       |      |          |                              |       | 2.0.8   |
| datapoints    | E_PRECIPITATION    |       | Type of precipitation                         |       |      |          |                              |       | 2.0.8   |
| datapoints    | E_TILT[1..x]       | °     | Sensor Tilt (relative to horizontal)          |       |      |          |                              |       | 2.0.8   |
| datapoints    | SLI_RAW[1..x]      | %     | Soiling Loss Raw                              |       |      |          |                              |       | 2.0.8   |
| datapoints    | SLI[1..x]          | %     | Soiling Loss                                  |       |      |          |                              |       | 2.0.8   |
| datapoints    | SNOW_LOAD[1..x]    | kg/m² | Snow load                                     |       |      |          |                              |       | 2.0.8   |
| datapoints    | SUN_H[1..x]        | h     | Sunshine duration                             |       |      |          |                              |       | 2.0.8   |
| datapoints    | QS_TX              |       | Telegrams transmitted (communication quality) |       |      |          |                              |       | 2.0.9   |
| datapoints    | QS_RX              |       | Telegrams received    (communication quality) |       |      |          |                              |       | 2.0.9   |
