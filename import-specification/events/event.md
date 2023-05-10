| Field Type | Name Attribute    | Description                                      | Type     | Required | Example                                                | Version | 
|------------|-------------------|--------------------------------------------------|----------|----------|--------------------------------------------------------|---------| 
| attribute  | timestamp         | Timestamp formatted as a subset of IETF RFC 3339 | datetime | x        | <event timestamp="2016-11-25T18:11:37Z" device-id="1"> | 2.2.2   | 
| attribute  | device-id         | Reference id for device data node                | string   | x        | <event timestamp="2016-11-25T18:11:37Z" device-id="1"> | 2.2.2   | 
| tag        | uid               | event uid                                        | string   |          | <uid>1ebc67e122cc1</uid>                               | 2.2.2   | 
| tag        | state             | event state                                      | string   |          | <state>off</state>                                     | 2.2.2   | 
| tag        | code              | event code                                       | string   |          | <code>100</code>                                       | 2.2.2   | 
| tag        | severity          | event severity                                   | string   |          | <severity>critical</severity>                          | 2.2.2   | 
| tag        | event-key         | event key                                        | string   |          | <event-key>v:VENDOR-s:SERIAL</event-key>               | 2.2.2   | 
| tag        | short-description | event short description                          | string   |          | <short-description>short message</short-description>   | 2.2.2   | 
| tag        | long-description  | event long description                           | string   |          | <long-description>long content</long-description>      | 2.2.2   | 
