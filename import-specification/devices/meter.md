| Field Type    | Name Attribute  | Unit   | Description                                                | Value | Type | Required | Example                      | Notes | Version | 
|---------------|-----------------|--------|------------------------------------------------------------|-------|------|----------|------------------------------|-------|---------| 
| configuration | id              |        | Reference id for measurement data node                     |       |      | x        | <device id=“1“ type=“meter“> |       | 2.0.1   | 
| configuration | type            |        | device type (inverter, meter, meteo, stringbox, battery)   |       |      | x        | <device id=“1“ type=“meter“> |       | 2.0.1   | 
| configuration | uid             |        | device unique identifier                                   |       |      | x        | <uid>MET12345</uid>          |       | 2.0.1   | 
| configuration | name            |        | device name                                                |       |      |          | <name>Meter A</name>         |       | 2.0.1   | 
| configuration | serial          |        | device serial                                              |       |      |          | <serial>MET11.22.33</serial> |       | 2.0.1   | 
| configuration | vendor          |        | device vendor                                              |       |      |          | <vendor>vendor 123</vendor>  |       | 2.0.1   | 
| configuration | model           |        | device model                                               |       |      |          | <model></model>              |       | 2.0.1   | 
| configuration | firmware        |        | device firmware                                            |       |      |          | <firmware>1.23.3</firmware>  |       | 2.0.1   | 
| datapoints    | M_AC_U          | V      | Volts A-N                                                  |       |      | x        |                              |       | 2.0.1   | 
| datapoints    | M_AC_U1         | V      | Volts A-N                                                  |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U2         | V      | Volts B-N                                                  |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U3         | V      | Volts C-N                                                  |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_I1         | A      | Amps A                                                     |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_I2         | A      | Amps B                                                     |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_I3         | A      | Amps C                                                     |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_I_N        | A      | Neutral Current                                            |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_P          | W      | Watts, 3-Ph total (Real Power)                             |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_P1         | W      | Active Power Phase 1                                       |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_P2         | W      | Active Power Phase 2                                       |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_P3         | W      | Active Power Phase 3                                       |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_Q          | VAr    | VARs, 3-Ph total (Reactive Power)                          |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_S          | VA     | Vas, 3-Ph total (Apparent Power)                           |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_PF_COSPHI  | cosphi | Power Factor (cos(phi))                                    |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_PF_COSPHI1 | cosphi | Power Factor 1 (cos(phi))                                  |       |      |          |                              |       | 2.0.8   | 
| datapoints    | M_AC_PF_COSPHI2 | cosphi | Power Factor 2 (cos(phi))                                  |       |      |          |                              |       | 2.0.8   | 
| datapoints    | M_AC_PF_COSPHI3 | cosphi | Power Factor 3 (cos(phi))                                  |       |      |          |                              |       | 2.0.8   | 
| datapoints    | M_AC_PF_TANPHI  | tanphi | Power Factor (tan(phi))                                    |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_PF_TANPHI1 | tanphi | Power Factor1 (tan(phi))                                   |       |      |          |                              |       | 2.0.8   | 
| datapoints    | M_AC_PF_TANPHI2 | tanphi | Power Factor2 (tan(phi))                                   |       |      |          |                              |       | 2.0.8   | 
| datapoints    | M_AC_PF_TANPHI3 | tanphi | Power Factor3 (tan(phi))                                   |       |      |          |                              |       | 2.0.8   | 
| datapoints    | M_AC_F          | Hz     | Frequency                                                  |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_E_EXP      | kWh    | kW-hours, Exported                                         |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_E_IMP      | kWh    | kW-hours, Imported                                         |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_EQ_CAP_EXP | kVArh  | kVAR-hours, Negative - Reactive Energy capacitive exported |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_EQ_CAP_IMP | kVArh  | kVAR-hours, Positive - Reactive Energy capacitive imported |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_EQ_IND_EXP | kVArh  | kVAR-hours, Positive - Reactive Energy inductive exported  |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_EQ_IND_IMP | kVArh  | kVAR-hours, Positive - Reactive Energy inductive imported  |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_ES_IMP     | kVAh   | kVA-hours - Apparent Power Imported                        |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_ES_EXP     | kVAh   | kVA-hours - Apparent Energy Exported                       |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_I_SF       | -      | CT Ratio (Scalefactor)                                     |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_I_DEN      | -      | CT Denominator                                             |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_I_NUM      | -      | CT Numerator                                               |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_I_MUL      | -      | CT Multiplier                                              |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U_SF       | -      | PT Ratio (Scalefactor)                                     |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U_DEN      | -      | PT Denominator                                             |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U_NUM      | -      | PT Numerator                                               |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U_MUL      | -      | PT Multiplier                                              |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U_L1L2     | V      | Volts L1-L2                                                |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U_L2L3     | V      | Volts L2-L3                                                |       |      |          |                              |       | 2.0.1   | 
| datapoints    | M_AC_U_L3L1     | V      | Volts L3-L1                                                |       |      |          |                              |       | 2.0.1   | 
| datapoints    | STATE[1..x]     |        | Global meter state conditions                              |       |      |          |                              |       | 2.0.1   | 
| datapoints    | ERROR[1..x]     |        | Global meter error conditions                              |       |      |          |                              |       | 2.0.1   | 