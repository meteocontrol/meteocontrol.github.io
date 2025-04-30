| Field Type            | Name Attribute       | Unit | Description                                   | Value    | Required | Example                         | Version |
|-----------------------|----------------------|------|-----------------------------------------------|----------|----------|---------------------------------|---------|
| configuration         | id                   |      | Reference id for measurement data node        |          | x        | <device id=“1“ type=“inverter“> | 2.0.1   |
| configuration         | type                 |      | device type                                   | inverter | x        | <device id=“1“ type=“inverter“> | 2.0.1   |
| configuration         | uid                  |      | device unique identifier                      |          | x        | <uid>INV12345</uid>             | 2.0.1   |
| configuration         | name                 |      | device name                                   |          |          | <name>Inverter A</name>         | 2.0.1   |
| configuration         | serial               |      | device serial                                 |          |          | <serial>INV11.22.33</serial>    | 2.0.1   |
| configuration         | vendor               |      | device vendor                                 |          |          | <vendor>vendor 123</vendor>     | 2.0.1   |
| configuration         | model                |      | device model                                  |          |          | <model></model>                 | 2.0.1   |
| configuration         | address              |      | bus address                                   |          |          | <address>1</address>            | 2.0.1   |
| configuration         | firmware             |      | device firmware                               |          |          | <firmware>1.23.3</firmware>     | 2.0.1   |
| datapoints            | `A_IN[1..x]`         |      | Analogue input                                |          |          |                                 |         |
| datapoints            | `COS_PHI`            |      | Cos Phi actual value                          |          |          |                                 |         |
| datapoints            | `COS_PHI_LOAD[1..3]` |      | Inductive or capacitive load (c/i)            |          |          |                                 |         |
| datapoints            | `COS_PHI_NOM[1..3]`  |      | Cos Phi given value                           |          |          |                                 |         |
| datapoints            | `D_IN[1..x]`         |      | Digital input                                 |          |          |                                 |         |
| datapoints            | `E_DAY`              | kWh  | Energy generated per day                      |          |          |                                 |         |
| datapoints            | `E_INT`              | kWh  | Energy generated per interval                 |          |          |                                 |         |
| datapoints            | `E_TOTAL`            | kWh  | Total generated energy                        |          |          |                                 |         |
| datapoints            | `E_YEAR`             | kWh  | Energy generated per year                     |          |          |                                 |         |
| datapoints            | `FT_AC_DAY`          | min  | Feed in Time Day AC                           |          |          |                                 |         |
| datapoints            | `FT_AC_TOTAL`        | hour | Feed in Time Total AC                         |          |          |                                 |         |
| datapoints            | `F_AC[1..x]`         | Hz   | Grid frequency (single phase or accumulated)  |          |          |                                 |         |
| datapoints            | `I_AC[1..x]`         | A    | Current AC (single phase or accumulated)      |          |          |                                 |         |
| datapoints            | `I_DC`               | A    | Current DC (accumulated)                      |          |          |                                 |         |
| datapoints            | `I_DC[1..x]`         | A    | Current DC MPPT x                             |          |          |                                 |         |
| datapoints            | `I_DC[1..x]_[1..x]`  | A    | Current DC MPPT x Input x                     |          |          |                                 |         |
| datapoints            | `I_GDFI`             | mA   | Earth leakage current                         |          |          |                                 |         |
| datapoints            | `OT_AC_DAY`          | min  | Operation Time DAY                            |          |          |                                 |         |
| datapoints            | `OT_AC_TOTAL`        | hour | Operation Time TOTAL                          |          |          |                                 |         |
| datapoints            | `P_AC[1..3]`         | W    | Power AC (single phase or accumulated)        |          | x        |                                 |         |
| datapoints            | `P_DC`               | W    | Power DC (accumulated)                        |          |          |                                 |         |
| datapoints            | `P_DC[1..x]`         | W    | Power DC MPPT x                               |          |          |                                 |         |
| datapoints            | `Q_AC[1..3]`         | var  | Reactive power (single phase or accumulated)  |          |          |                                 |         |
| datapoints            | `R_AC`               | mOhm | Grid impedance                                |          |          |                                 |         |
| datapoints            | `R_ISO`              | kOhm | Isolation resistant                           |          |          |                                 |         |
| datapoints            | `S_AC[1..3]`         | VA   | Apparent power (single phase or accumulated)  |          |          |                                 |         |
| datapoints            | `T[1..x]`            | °C   | inverter temperatures                         |          |          |                                 |         |
| datapoints            | `T_WR[1..x]`         | °C   | inverter temperatures                         |          |          |                                 |         |
| datapoints            | `U_AC[1..3]`         | V    | Voltage AC (single phase or accumulated)      |          |          |                                 |         |
| datapoints            | `U_AC_L1L2`          | V    | Volts L1-L2                                   |          |          |                                 |         |
| datapoints            | `U_AC_L2L3`          | V    | Volts L2-L3                                   |          |          |                                 |         |
| datapoints            | `U_AC_L3L1`          | V    | Volts L3-L1                                   |          |          |                                 |         |
| datapoints            | `U_DC`               | V    | Voltage DC (accumulated)                      |          |          |                                 |         |
| datapoints            | `U_DC[1..x]`         | V    | Voltage DC MPPT x                             |          |          |                                 |         |
| datapoints            | `U_DC[1..x]_[1..x]`  | V    | Voltage DC MPPT x Input x                     |          |          |                                 |         |
| datapoints            | `U_DC_NE`            | V    | Voltage DC negative pole to earth             |          |          |                                 |         |
| datapoints            | `U_DC_PE`            | V    | Voltage DC positive pole to earth             |          |          |                                 |         |
| datapoints            | `STATE[1..x]`        |      | Global inverter state conditions              |          |          |                                 |         |
| datapoints            | `ERROR[1..x]`        |      | Global inverter error conditions              |          |          |                                 |         |
| datapoints            | `QS_TX`              |      | Telegrams transmitted (communication quality) |          |          |                                 |         |
| datapoints            | `QS_RX`              |      | Telegrams received (communication quality)    |          |          |                                 |         |
| deprecated datapoints | `PC`                 | %    | Power Control                                 |          |          |                                 |         |
