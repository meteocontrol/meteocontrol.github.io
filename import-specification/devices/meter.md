| Field Type    | Name Attribute       | Unit   | Description                                                | Value | Required | Example                      | Version |
|---------------|----------------------|--------|------------------------------------------------------------|-------|----------|------------------------------|---------|
| configuration | id                   |        | Reference id for measurement data node                     |       | x        | <device id=“1“ type=“meter“> | 2.0.1   |
| configuration | type                 |        | device type                                                | meter | x        | <device id=“1“ type=“meter“> | 2.0.1   |
| configuration | uid                  |        | device unique identifier                                   |       | x        | <uid>MET12345</uid>          | 2.0.1   |
| configuration | name                 |        | device name                                                |       |          | <name>Meter A</name>         | 2.0.1   |
| configuration | serial               |        | device serial                                              |       |          | <serial>MET11.22.33</serial> | 2.0.1   |
| configuration | vendor               |        | device vendor                                              |       |          | <vendor>vendor 123</vendor>  | 2.0.1   |
| configuration | model                |        | device model                                               |       |          | <model></model>              | 2.0.1   |
| configuration | address              |        | bus address                                                |       |          | <address>1</address>         | 2.0.1   |
| configuration | firmware             |        | device firmware                                            |       |          | <firmware>1.23.3</firmware>  | 2.0.1   |
| datapoints    | M_AC_EQ_CAP_EXP      | kVArh  | kVAR-hours, Negative - Reactive Energy capacitive exported |       |          |                              |         |
| datapoints    | M_AC_EQ_CAP_IMP      | kVArh  | kVAR-hours, Positive - Reactive Energy capacitive imported |       |          |                              |         |
| datapoints    | M_AC_EQ_IND_EXP      | kVArh  | kVAR-hours, Positive - Reactive Energy inductive exported  |       |          |                              |         |
| datapoints    | M_AC_EQ_IND_IMP      | kVArh  | kVAR-hours, Positive - Reactive Energy inductive imported  |       |          |                              |         |
| datapoints    | M_AC_EQ_TOTAL        | kVArh  | kVAR-hours - Reactive Energy total                         |       |          |                              |         |
| datapoints    | M_AC_ES_EXP          | kVAh   | kVA-hours - Apparent Energy Exported                       |       |          |                              |         |
| datapoints    | M_AC_ES_IMP          | kVAh   | kVA-hours - Apparent Energy Imported                       |       |          |                              |         |
| datapoints    | M_AC_E_EXP[1..x]     | kWh    | kW-hours, Exported                                         |       |          |                              |         |
| datapoints    | M_AC_E_IMP[1..x]     | kWh    | kW-hours, Imported                                         |       |          |                              |         |
| datapoints    | M_AC_F[1..x]         | Hz     | Frequency                                                  |       |          |                              |         |
| datapoints    | M_AC_I[1..3]         | A      | Current [Phase 1-3]                                        |       |          |                              |         |
| datapoints    | M_AC_I_N             | A      | Neutral Current                                            |       |          |                              |         |
| datapoints    | M_AC_I_SF            |        | CT Ratio (Scalefactor)                                     |       |          |                              |         |
| datapoints    | M_AC_OT_TOTAL        | hour   | Operation Time TOTAL                                       |       |          |                              |         |
| datapoints    | M_AC_P[1..3]         | W      | Active Power [Phase 1-3]                                   |       |          |                              |         |
| datapoints    | M_AC_PF_COSPHI[1..x] | cosphi | Power Factor (cos(phi))                                    |       |          |                              |         |
| datapoints    | M_AC_PF_TANPHI       | tanphi | Power Factor (tanphi)                                      |       |          |                              |         |
| datapoints    | M_AC_Q[1..3]         | VAr    | Reactive Power [Phase 1-3]                                 |       |          |                              |         |
| datapoints    | M_AC_S[1..3]         | VA     | Apparent Power [Phase 1-3]                                 |       |          |                              |         |
| datapoints    | M_AC_U[1..3]         | V      | Voltage, Phase [1-3]                                       |       |          |                              |         |
| datapoints    | M_AC_U_L1L2          | V      | Volts L1-L2                                                |       |          |                              |         |
| datapoints    | M_AC_U_L2L3          | V      | Volts L2-L3                                                |       |          |                              |         |
| datapoints    | M_AC_U_L3L1          | V      | Volts L3-L1                                                |       |          |                              |         |
| datapoints    | M_DC_E_EXP           | kWh    | Active Energy DC (export)                                  |       |          |                              |         |
| datapoints    | M_DC_E_IMP           | kWh    | Active Energy DC (import)                                  |       |          |                              |         |
| datapoints    | M_DC_I[1..3]         | A      | Current DC [Phase 1-3]                                     |       |          |                              |         |
| datapoints    | M_DC_P[1..3]         | W      | Power DC [Phase 1-3]                                       |       |          |                              |         |
| datapoints    | M_DC_U[1..3]         | V      | Voltage DC, Phase [1-3]                                    |       |          |                              |         |
| datapoints    | M_EQ_CAP_INT_EXP     | kVArh  | Reactive Energy Lead                                       |       |          |                              |         |
| datapoints    | M_EQ_IND_INT_EXP     | kVArh  | Reactive Energy Lag                                        |       |          |                              |         |
| datapoints    | STATE[1..x]          |        |                                                            |       |          |                              |         |
| datapoints    | ERROR[1..x]          |        | Global meter error conditions                              |       |          |                              |         |
| datapoints    | QS_TX                |        | Telegrams transmitted (communication quality)              |       |          |                              |         |
| datapoints    | QS_RX                |        | Telegrams received (communication quality)                 |       |          |                              |         |
