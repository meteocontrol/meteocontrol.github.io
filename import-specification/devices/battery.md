| Field Type    | Name Attribute | Unit | Description                                              | Value | Type | Required | Example                            | Notes | Version | 
|---------------|----------------|------|----------------------------------------------------------|-------|------|----------|------------------------------------|-------|---------| 
| configuration | id             |      | Reference id for measurement data node                   |       |      | x        | <device id=“**1**“ type=“battery“> |       | 2.0.1   | 
| configuration | type           |      | device type (inverter, meter, meteo, stringbox, battery) |       |      | x        | <device id=“1“ type=“battery“>     |       | 2.0.1   | 
| configuration | uid            |      | device unique identifier                                 |       |      | x        | <uid>BAT12345</uid>                |       | 2.0.1   | 
| configuration | name           |      | device name                                              |       |      |          | <name>Battery A</name>             |       | 2.0.1   | 
| configuration | serial         |      | device serial                                            |       |      |          | <serial>BAT11.22.33</serial>       |       | 2.0.1   | 
| configuration | vendor         |      | device vendor                                            |       |      |          | <vendor>vendor 123</vendor>        |       | 2.0.1   | 
| configuration | model          |      | device model                                             |       |      |          | <model></model>                    |       | 2.0.1   | 
| configuration | firmware       |      | device firmware                                          |       |      |          | <firmware>1.23.3</firmware>        |       | 2.0.1   | 
| datapoints    | B_E_IMP        | kWh  | Total energy to stacks                                   |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_E_EXP        | kWh  | Total energy from stacks                                 |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_CHARGE_LEVEL | %    | Charge level                                             |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_CAPACITY     | Ah   | Nominal capacity                                         |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_E_STORED     | kWh  | Currently stored energy                                  |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_U_BULK       | V    | Battery charging voltage DC                              |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_U_DC         | V    | Battery voltage                                          |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_U_OC         | V    | Open circuit voltage                                     |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_OT_TOTAL     | h    | Operating hours                                          |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | B_P_DC         | W    | Total battery power                                      |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | T[1..x]        | °C   | Temperatures                                             |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | STATE[1..x]    |      | Global battery state conditions                          |       |      |          |                                    |       | 2.0.1   | 
| datapoints    | ERROR[1..x]    |      | Global battery error conditions                          |       |      |          |                                    |       | 2.0.1   |
| datapoints    | QS_TX             |       | Telegrams transmitted (communication quality)         |       |       |          |                                |       | 2.0.9   |
| datapoints    | QS_RX             |       | Telegrams received    (communication quality)         |       |       |          |                                |       | 2.0.9   |
