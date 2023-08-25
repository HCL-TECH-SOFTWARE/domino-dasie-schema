<!--
   Copyright 2023 HCL America, Inc.

   Licensed under the Apache License, Version 2.0 (the "License"); you may not
   use this file except in compliance with the License. You may obtain a copy of
   the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
   WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
   License for the specific language governing permissions and limitations under
   the License.
-->

# CDCOLOR

A
[CDCOLOR](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDCOLOR/).

## Examples
```yaml
type: 0x00d2
Color:
  Flags: 0x0001
  rgb: 0x424282
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `Color`
* type: [COLOR_VALUE](../values/color_value.md)
* see:
[CDCOLOR](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDCOLOR/)

### `type`
The signature type of the record.
* type: number
* value: 0x00D2
* see:
[SIG_CD_COLOR](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)
