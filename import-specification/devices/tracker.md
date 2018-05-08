| Field Type    | Name Attribute   | Unit | Description                             | Value     | Required  | Example                           | Version |
|---------------|------------------|------|-----------------------------------------|-----------|-----------|-----------------------------------|---------|
| configuration | id               |      | Reference id for measurement data node  |           | x         | <device id=“1“ type=“tracker“>    | 2.0.1 |
| configuration | type             |      | device type                             | tracker   | x         | <device id=“1“ type=“tracker“>    | 2.0.1 |
| configuration | uid              |      | device unique identifier                |           | x         | <uid>TRK12345</uid>               | 2.0.1 |
| configuration | name             |      | device name                             |           |           | <name>Tracker A</name>            | 2.0.1 |
| configuration | serial           |      | device serial                           |           |           | <serial>TRK11.22.33</serial>      | 2.0.1 |
| configuration | vendor           |      | device vendor                           |           |           | <vendor>vendor 123</vendor>       | 2.0.1 |
| configuration | model            |      | device model                            |           |           | <model>Model A1.3</model>         | 2.0.1 |
| configuration | firmware         |      | device firmware                         |           |           | <firmware>1.23.3</firmware>       | 2.0.1 |
| datapoints    | TRACKER_TYPE     | enum | Type of tracker (<br>0 = Unknown / Not Set, <br>1 = Fixed / Documented orientation information, <br>2 = Single Axis Horizontal, <br>3 = Single Axis Tilted Horizontal, <br>4 = Single Axis Azimuth, <br>5 = Dual Axis, <br>99 = Other type<br>) ||||  2.0.1 |
| datapoints    | ELEVATION_TARGET | °  | Auto target elevation in degrees from horizontal.Unimplemented for single axis azimuth tracker type ||||  2.0.1 |
| datapoints    | ELEVATION_MANUAL | °  | Global manual override target position of elevation in degreees from horizontal.Unimplemented for single axis azimuth tracker type |||| 2.0.1 |
| datapoints    | ELEVATION        | °  | Actual elevation positionin degrees from horizontal.Unimplemented for single axis azimuth tracker type |||| 2.0.1 |
| datapoints    | AZIMUTH _TARGET  | °  | Auto target azimuthin degrees from true north towards east.Unimplemented for single axis horizontal tracker type |||| 2.0.1 |
| datapoints    | AZIMUTH_MANUAL   | °  | Global manual override target position of azimuth in degrees from true north towards east. Unimplemented for single axis azimuth tracker type |||| 2.0.1 |
| datapoints    | AZIMUTH          | °  | Actual azimuth positionin degrees from true north towards east.Unimplemented for single axis horizontal tracker type |||| 2.0.1 |
| datapoints    | MODE             | enum | auto = Follow programmed path <br>manual = Go to a fixed position, <br>storm = Go to a fixed position, <br>calibrate = Execute test mode ||||  2.0.1 |
| datapoints    | STATE[1..x]      |      | Global tracker state conditions         |           |           |                                   | 2.0.1 |
| datapoints    | ERROR[1..x]      |      | Global tracker error conditions         |           |           |                                   | 2.0.1 |
| datapoints    | QS_TX            |      | Telegrams transmitted (communication quality) |     |           |                                   | 2.0.9 |
| datapoints    | QS_RX            |      | Telegrams received(communication quality) |         |           |                                   | 2.0.9 |

