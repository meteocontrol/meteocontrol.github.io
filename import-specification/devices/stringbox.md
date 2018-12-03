| Field Type    | Name Attribute | Unit | Description                                                       | Value     | Required | Example                          | Version |
|---------------|----------------|------|-------------------------------------------------------------------|-----------|----------|----------------------------------|---------|
| configuration | id             |      | Reference id for measurement data node                            |           | x        | <device id=“1“ type=“stringbox“> | 2.0.1   |
| configuration | type           |      | device type                                                       | stringbox | x        | <device id=“1“ type=“stringbox“> | 2.0.1   |
| configuration | uid            |      | device unique identifier                                          |           | x        | <uid>STR12345</uid>              | 2.0.1   |
| configuration | name           |      | device name                                                       |           |          | <name>Stringbox A</name>         | 2.0.1   |
| configuration | serial         |      | device serial                                                     |           |          | <serial>STR11.22.33</serial>     | 2.0.1   |
| configuration | vendor         |      | device vendor                                                     |           |          | <vendor>vendor 123</vendor>      | 2.0.1   |
| configuration | model          |      | device model                                                      |           |          | <model></model>                  | 2.0.1   |
| configuration | firmware       |      | device firmware                                                   |           |          | <firmware>1.23.3</firmware>      | 2.0.1   |
| datapoints    | A_IN[1..x]     |      | Optional analogue inputs                                          |           |          |                                  |         |
| datapoints    | D_IN[1..x]     |      | Digital input                                                     |           |          |                                  |         |
| datapoints    | I[1..x]        | A    | Current value of string 1..x (`I` without number is not allowed)  |           | x        |                                  |         |
| datapoints    | I_AVG          | A    | Average value of all string values                                |           |          |                                  |         |
| datapoints    | I_SUM          | A    | Sum of all string values                                          |           |          |                                  |         |
| datapoints    | P_DC           | W    | DC-Power	                                                         |           |          |                                  |         |
| datapoints    | T[1..x]        | °C   | Temperatures                                                      |           |          |                                  |         |
| datapoints    | U_DC           | V    | DC-Voltage                                                        |           |          |                                  |         |
| datapoints    | STATE[1..x]    |      | Global strongbox state conditions                                 |           |          |                                  |         |
| datapoints    | ERROR[1..x]    |      | Global stringbox error conditions                                 |           |          |                                  |         |
| datapoints    | QS_TX          |      | Telegrams transmitted (communication quality)                     |           |          |                                  |         |
| datapoints    | QS_RX          |      | Telegrams received (communication quality)                        |           |          |                                  |         |
