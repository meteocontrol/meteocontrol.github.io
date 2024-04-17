| Field Type    | Name Attribute     | Unit  | Description                                        | Value  | Required | Example                       | Version |
|---------------|--------------------|-------|----------------------------------------------------|--------|----------|-------------------------------|---------|
| configuration | id                 |       | Reference id for measurement data node             |        | x        | <device id=“1“ type=“genset“> | 2.0.9   |
| configuration | type               |       | device type                                        | genset | x        | <device id=“1“ type=“genset“> | 2.0.9   |
| configuration | uid                |       | device unique identifier                           |        | x        | <uid>GEN12345</uid>           | 2.0.9   |
| configuration | name               |       | device name                                        |        |          | <name>Genset A</name>         | 2.0.9   |
| configuration | serial             |       | device serial                                      |        |          | <serial>GEN11.22.33</serial>  | 2.0.9   |
| configuration | vendor             |       | device vendor                                      |        |          | <vendor>Vendor 123</vendor>   | 2.0.9   |
| configuration | model              |       | device model                                       |        |          | <model>Model ABC</model>      | 2.0.9   |
| configuration | address            |       | bus address                                        |        |          | <address>1</address>          | 2.0.9   |
| configuration | firmware           |       | device firmware                                    |        |          | <firmware>1.23.3</firmware>   | 2.0.9   |
| datapoints    | `COS_PHI`          |       | Power factor cos phi                               |        |          |                               |         |
| datapoints    | `E_INT`            | kWh   | Yield in current interval                          |        |          |                               |         |
| datapoints    | `E_TOTAL`          | kWh   | Total yield                                        |        |          |                               |         |
| datapoints    | `FUEL_CONSUMPTION` | l/h   | Fuel consumption                                   |        |          |                               |         |
| datapoints    | `FUEL_EFFICIENCY`  | kWh/l | Fuel efficiency                                    |        |          |                               |         |
| datapoints    | `FUEL_REMAINING`   | %     | Fuel remaining                                     |        |          |                               |         |
| datapoints    | `F_AC[1..3]`       | Hz    | Grid frequency (single phase or accumulated)       |        |          |                               |         |
| datapoints    | `I_AC[1..3]`       | A     | Current AC (single phase or accumulated)           |        |          |                               |         |
| datapoints    | `OT_REMAINING`     | h     | Operation hours remaining                          |        |          |                               |         |
| datapoints    | `OT_TOTAL`         | h     | Operation hours                                    |        |          |                               |         |
| datapoints    | `P_AC[1..3]`       | W     | Power AC (single phase or accumulated)             |        |          |                               |         |
| datapoints    | `P_AC_SET_ABS`     | W     | Absolute active power setpoint                     |        |          |                               |         |
| datapoints    | `P_AC_SET_REL`     | %     | Relative active power setpoint                     |        |          |                               |         |
| datapoints    | `Q_AC[1..3]`       | var   | Total reactive power (single phase or accumulated) |        |          |                               |         |
| datapoints    | `Q_AC_SET_ABS`     | var   | Absolute reactive power setpoint                   |        |          |                               |         |
| datapoints    | `S_AC[1..3]`       | VA    | Total apparent power (single phase or accumulated) |        |          |                               |         |
| datapoints    | `U_AC[1..3]`       | V     | Voltage AC (single phase or accumulated)           |        |          |                               |         |
| datapoints    | `U_AC_L1L2`        | V     | Voltage phase 1-2                                  |        |          |                               |         |
| datapoints    | `U_AC_L2L3`        | V     | Voltage phase 2-3                                  |        |          |                               |         |
| datapoints    | `U_AC_L3L1`        | V     | Voltage phase 3-1                                  |        |          |                               |         |
| datapoints    | `STATE[1..x]`      |       | Global inverter genset conditions                  |        |          |                               |         |
| datapoints    | `ERROR[1..x]`      |       | Global genset error conditions                     |        |          |                               |         |
| datapoints    | `QS_TX`            |       | Telegrams transmitted (communication quality)      |        |          |                               |         |
| datapoints    | `QS_RX`            |       | Telegrams received (communication quality)         |        |          |                               |         |
