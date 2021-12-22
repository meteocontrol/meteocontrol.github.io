| Field Type    | Name Attribute                 | Unit | Description                                     | Value   | Required | Example                        | Version |
|---------------|--------------------------------|------|-------------------------------------------------|---------|----------|--------------------------------|---------|
| configuration | id                             |      | Reference id for measurement data node          |         | x        | <device id=“1“ type=“battery“> | 2.0.1   |
| configuration | type                           |      | device type                                     | battery | x        | <device id=“1“ type=“battery“> | 2.0.1   |
| configuration | uid                            |      | device unique identifier                        |         | x        | <uid>BAT12345</uid>            | 2.0.1   |
| configuration | name                           |      | device name                                     |         |          | <name>Battery A</name>         | 2.0.1   |
| configuration | serial                         |      | device serial                                   |         |          | <serial>BAT11.22.33</serial>   | 2.0.1   |
| configuration | vendor                         |      | device vendor                                   |         |          | <vendor>vendor 123</vendor>    | 2.0.1   |
| configuration | model                          |      | device model                                    |         |          | <model></model>                | 2.0.1   |
| configuration | address                        |      | bus address                                     |         |          | <address>1</address>           | 2.0.1   |
| configuration | firmware                       |      | device firmware                                 |         |          | <firmware>1.23.3</firmware>    | 2.0.1   |
| datapoints    | `B_CAPACITY`                   | Ah   | Nominal capacity                                |         |          |                                |         |
| datapoints    | `B_E_CHARGE_AC`                | kWh  | Chargeable Energy                               |         |          |                                |         |
| datapoints    | `B_E_DISCHARGE_AC`             | kWh  | Dischargeable Energy                            |         |          |                                |         |
| datapoints    | `B_E_EXP`                      | kWh  | Energy export from storage system DC            |         |          |                                |         |
| datapoints    | `B_E_EXP_AC`                   | kWh  | Energy export from storage system AC            |         |          |                                |         |
| datapoints    | `B_E_IMP`                      | kWh  | Energy import to storage system DC              |         |          |                                |         |
| datapoints    | `B_E_IMP_AC`                   | kWh  | Energy import to storage system AC              |         |          |                                |         |
| datapoints    | `B_E_INT_EXP`                  | kWh  | Energy export from storage system (interval) DC |         |          |                                |         |
| datapoints    | `B_E_INT_EXP_AC`               | kWh  | Energy export from storage system (interval) AC |         |          |                                |         |
| datapoints    | `B_E_INT_IMP`                  | kWh  | Energy import to storage system (interval) DC   |         |          |                                |         |
| datapoints    | `B_E_INT_IMP_AC`               | kWh  | Energy import to storage system (interval) AC   |         |          |                                |         |
| datapoints    | `B_E_STORED`                   | kWh  | Currently stored energy                         |         |          |                                |         |
| datapoints    | `B_F_AC`                       | Hz   | Grid frequency                                  |         |          |                                |         |
| datapoints    | `B_I_AC`                       | A    | Battery AC current                              |         |          |                                |         |
| datapoints    | `B_I_DC`                       | A    | Charging current DC                             |         |          |                                |         |
| datapoints    | `B_LIM_I_CHARGE`               |      | Maximum charging current                        |         |          |                                |         |
| datapoints    | `B_LIM_I_DISCHARGE`            |      | Maximum discharging current                     |         |          |                                |         |
| datapoints    | `B_LIM_P_CHARGE`               | W    | Maximum charging power                          |         |          |                                |         |
| datapoints    | `B_LIM_P_DISCHARGE`            | W    | Maximum discharging power                       |         |          |                                |         |
| datapoints    | `B_LIM_U_CHARGE`               | V    | Charge end voltage                              |         |          |                                |         |
| datapoints    | `B_LIM_U_DISCHARGE`            |      | Discharge end voltage                           |         |          |                                |         |
| datapoints    | `B_OT_TOTAL`                   | h    | Operating Hours                                 |         |          |                                |         |
| datapoints    | `B_P_AC`                       | W    | Battery power AC                                |         |          |                                |         |
| datapoints    | `B_P_DC`                       | W    | Total battery power                             |         |          |                                |         |
| datapoints    | `B_Q_AC`                       | VAr  | Battery reactive power AC                       |         |          |                                |         |
| datapoints    | `B_SOC`                        | %    | State of Charge                                 |         |          |                                |         |
| datapoints    | `B_SOCH`                       | %    | State of charge (nominal capacity)              |         |          |                                |         |
| datapoints    | `B_SOH`                        | %    | State of health                                 |         |          |                                |         |
| datapoints    | `B_S_AC`                       | VA   | Battery apparent power AC                       |         |          |                                |         |
| datapoints    | `B_T_CELL[1..x]_[1..x]_[1..x]` | °C   | Cell temperature  [°C]                          |         |          |                                |         |
| datapoints    | `B_T_CELL_MAX[1..x]_[1..x]`    | °C   | Maximum cell temperature  [°C]                  |         |          |                                |         |
| datapoints    | `B_T_CELL_MIN[1..x]_[1..x]`    | °C   | Minimum cell temperature  [°C]                  |         |          |                                |         |
| datapoints    | `B_T_M[1..x]_[1..x]`           | °C   | Module temperature [°C]                         |         |          |                                |         |
| datapoints    | `B_T_M_MAX[1..x]`              | °C   | Maximum module temperature [°C]                 |         |          |                                |         |
| datapoints    | `B_T_M_MIN[1..x]`              | °C   | Minimum module temperature [°C]                 |         |          |                                |         |
| datapoints    | `B_T_U[1..x]`                  | °C   | Temperature Outside/ Ambient [°C]               |         |          |                                |         |
| datapoints    | `B_U_AC`                       | V    | Battery AC voltage                              |         |          |                                |         |
| datapoints    | `B_U_BULK`                     | V    | Battery charging voltage DC                     |         |          |                                |         |
| datapoints    | `B_U_CELL[1..x]_[1..x]_[1..x]` | V    | Cell voltage                                    |         |          |                                |         |
| datapoints    | `B_U_CELL_AVG`                 | V    | Average cell voltage                            |         |          |                                |         |
| datapoints    | `B_U_CELL_MAX[1..x]_[1..x]`    | V    | Maximum cell voltage                            |         |          |                                |         |
| datapoints    | `B_U_CELL_MIN[1..x]_[1..x]`    | V    | Minimum cell voltage                            |         |          |                                |         |
| datapoints    | `B_U_DC`                       | V    | Battery voltage                                 |         |          |                                |         |
| datapoints    | `B_U_OC`                       | V    | Open circuit voltage                            |         |          |                                |         |
| datapoints    | `T[1..x]`                      | °C   | Temperatures                                    |         |          |                                |         |
| datapoints    | `STATE[1..x]`                  |      | Global battery state conditions                 |         |          |                                |         |
| datapoints    | `ERROR[1..x]`                  |      | Global battery error conditions                 |         |          |                                |         |
| datapoints    | `QS_TX`                        |      | Telegrams transmitted (communication quality)   |         |          |                                |         |
| datapoints    | `QS_RX`                        |      | Telegrams received (communication quality)      |         |          |                                |         |
