| Field Type    | Name Attribute            | Unit  | Description                                                              | Value | Required | Example                      | Version |
|---------------|---------------------------|-------|--------------------------------------------------------------------------|-------|----------|------------------------------|---------|
| configuration | id                        |       | Reference id for measurement data node                                   |       | x        | <device id=“1“ type=“meteo“> | 2.0.1   |
| configuration | type                      |       | device type                                                              | meteo | x        | <device id=“1“ type=“meteo“> | 2.0.1   |
| configuration | uid                       |       | device unique identifier                                                 |       | x        | <uid>MET12345</uid>          | 2.0.1   |
| configuration | name                      |       | device name                                                              |       |          | <name>Meteo A</name>         | 2.0.1   |
| configuration | serial                    |       | device serial                                                            |       |          | <serial>MET11.22.33</serial> | 2.0.1   |
| configuration | vendor                    |       | device vendor                                                            |       |          | <vendor>vendor 123</vendor>  | 2.0.1   |
| configuration | model                     |       | device model                                                             |       |          | <model></model>              | 2.0.1   |
| configuration | address                   |       | bus address                                                              |       |          | <address>1</address>         | 2.0.1   |
| configuration | firmware                  |       | device firmware                                                          |       |          | <firmware>1.23.3</firmware>  | 2.0.1   |
| datapoints    | `E_AH_ABS[1..x]`          | g/m³  | Absolute humidity                                                        |       |          |                              |         |
| datapoints    | `E_AH_REL[1..x]`          | %     | Relative humidity                                                        |       |          |                              |         |
| datapoints    | `E_ALT[1..x]`             | m     | Local height                                                             |       |          |                              |         |
| datapoints    | `E_AP_ABS[1..x]`          | hPa   | Absolute air pressure                                                    |       |          |                              |         |
| datapoints    | `E_AP_REL[1..x]`          | hPa   | Relative air pressure                                                    |       |          |                              |         |
| datapoints    | `E_AT[1..x]`              | °C    | Air temperature                                                          |       |          |                              |         |
| datapoints    | `E_DEWPOINT`              | °C    | Dewpoint                                                                 |       |          |                              |         |
| datapoints    | `E_F_S[1..x]`             | rpm   | Fan speed                                                                |       |          |                              |         |
| datapoints    | `E_IH_REL[1..x]`          | %     | Internal relative humidity                                               |       |          |                              |         |
| datapoints    | `E_IP_ABS[1..x]`          | hPa   | Internal air pressure                                                    |       |          |                              |         |
| datapoints    | `E_LIGHTNING_COUNT`       |       | Lightning events interval                                                |       |          |                              |         |
| datapoints    | `E_LIGHTNING_COUNT_TOTAL` |       | Lightning events total                                                   |       |          |                              |         |
| datapoints    | `E_PRECIPITATION`         |       | Type of precipitation (0 = None; 10 = Rain; 20 = Snow; 30 = Unspecified) |       |          |                              |         |
| datapoints    | `E_RF_ABS[1..x]`          | mm    | Absolute precipitation                                                   |       |          |                              |         |
| datapoints    | `E_RF_DIF[1..x]`          | mm    | Differential precipitation                                               |       |          |                              |         |
| datapoints    | `E_RF_I[1..x]`            | mm/h  | Precipitation intensity                                                  |       |          |                              |         |
| datapoints    | `E_SNOW_DEPTH[1..x]`      | m     | Snow depth                                                               |       |          |                              |         |
| datapoints    | `E_TILT[1..x]`            | °     | Sensor Tilt (relative to horizontal)                                     |       |          |                              |         |
| datapoints    | `E_W_D[1..x]`             | °     | Wind direction                                                           |       |          |                              |         |
| datapoints    | `E_W_S[1..x]`             | m/s   | Wind speed                                                               |       |          |                              |         |
| datapoints    | `E_W_S[1..x]_MAX`         | m/s   | Maximum wind speed                                                       |       |          |                              |         |
| datapoints    | `SLI[1..x]`               | %     | Soiling Loss                                                             |       |          |                              |         |
| datapoints    | `SLI_RAW[1..x]`           | %     | Soiling Loss Raw                                                         |       |          |                              |         |
| datapoints    | `SNOW_LOAD[1..x]`         | kg/m² | Snow load                                                                |       |          |                              |         |
| datapoints    | `SRAD[1..x]`              | W/m2  | Irradiation sensors                                                      |       |          |                              |         |
| datapoints    | `SR[1..x]`                | %     | Soiling ratio                                                            |       |          |                              |         |
| datapoints    | `SUN_H[1..x]`             | h     | Sunshine duration                                                        |       |          |                              |         |
| datapoints    | `T[1..x]`                 | °C    | Temperature values                                                       |       |          |                              |         |
| datapoints    | `WATER_DEPTH`             | m     | Water depth                                                              |       |          |                              |         |
| datapoints    | `STATE[1..x]`             |       |                                                                          |       |          |                              |         |
| datapoints    | `ERROR[1..x]`             |       | Global meteo error conditions                                            |       |          |                              |         |
| datapoints    | `QS_TX`                   |       | Telegrams transmitted (communication quality)                            |       |          |                              |         |
| datapoints    | `QS_RX`                   |       | Telegrams received (communication quality)                               |       |          |                              |         |
