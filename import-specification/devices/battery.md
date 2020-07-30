| Field Type    | Name Attribute | Unit | Description                                   | Value   | Required | Example                        | Version |
|---------------|----------------|------|-----------------------------------------------|---------|----------|--------------------------------|---------|
| configuration | id             |      | Reference id for measurement data node        |         | x        | <device id=“1“ type=“battery“> | 2.0.1   |
| configuration | type           |      | device type                                   | battery | x        | <device id=“1“ type=“battery“> | 2.0.1   |
| configuration | uid            |      | device unique identifier                      |         | x        | <uid>BAT12345</uid>            | 2.0.1   |
| configuration | name           |      | device name                                   |         |          | <name>Battery A</name>         | 2.0.1   |
| configuration | serial         |      | device serial                                 |         |          | <serial>BAT11.22.33</serial>   | 2.0.1   |
| configuration | vendor         |      | device vendor                                 |         |          | <vendor>vendor 123</vendor>    | 2.0.1   |
| configuration | model          |      | device model                                  |         |          | <model></model>                | 2.0.1   |
| configuration | address        |      | bus address                                   |         |          | <address>1</address>           | 2.0.1   |
| configuration | firmware       |      | device firmware                               |         |          | <firmware>1.23.3</firmware>    | 2.0.1   |
| datapoints    | B_CAPACITY     | Ah   | Nominal capacity                              |         |          |                                |         |
| datapoints    | B_CHARGE_LEVEL | %    | Charge Level                                  |         |          |                                |         |
| datapoints    | B_E_EXP        | kWh  | Total energy from stacks                      |         |          |                                |         |
| datapoints    | B_E_IMP        | kWh  | Total energy to stacks                        |         |          |                                |         |
| datapoints    | B_E_STORED     | kWh  | Currently stored energy                       |         |          |                                |         |
| datapoints    | B_I_DC         | A    | Ladestrom (DC)                                |         |          |                                |         |
| datapoints    | B_OT_TOTAL     | h    | Operating Hours                               |         |          |                                |         |
| datapoints    | B_P_DC         | W    | Total battery power                           |         |          |                                |         |
| datapoints    | B_U_BULK       | V    | Battery charging voltage DC                   |         |          |                                |         |
| datapoints    | B_U_DC         | V    | Battery voltage                               |         |          |                                |         |
| datapoints    | B_U_OC         | V    | Open circuit voltage                          |         |          |                                |         |
| datapoints    | T[1..x]        | °C   | Temperatures                                  |         |          |                                |         |
| datapoints    | STATE[1..x]    |      | Global battery state conditions               |         |          |                                |         |
| datapoints    | ERROR[1..x]    |      | Global battery error conditions               |         |          |                                |         |
| datapoints    | QS_TX          |      | Telegrams transmitted (communication quality) |         |          |                                |         |
| datapoints    | QS_RX          |      | Telegrams received (communication quality)    |         |          |                                |         |
