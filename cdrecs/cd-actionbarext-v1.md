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

# CDACTION

A
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/).

## Examples
```yaml
type: 0xff79
BackColor:
  Flags: 0x0001
  rgb: 0xffff00
BtnBorderDisplay: 0
BtnTextJustify: 0
BtnWidthStyle: 0
ButtonColor:
  Flags: 0x0001
  rgb: 0xf0f0f0
FontColor:
  Flags: 0x0009
  rgb: 0x000000
LineColor:
  Flags: 0x0001
  rgb: 0x000000
Spare:
  - 0x00000000
  - 0x00000000
  - 0x00000000
  - 0x00000000
  - 0x00000000
  - 0x00000000
  - 0x00000000
  - 0x00000000
  - 0x00000000
  - 0x00000000
  - 0x00000000
barFontID: 0x00000000
barHeight:
  Flags: 0x0000
  Length:
    - 0
    - 0
    - 0
    - 0
    - 0
    - 0
    - 0
    - 0
  Reserved: 0
  Units: 0
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `BackColor`
* type: [COLOR_VALUE](../values/color_value.md)
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `BtnBorderDisplay`
* type: number
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `BtnTextJustify`
* type: number
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `BtnWidthStyle`
* type: number
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `ButtonColor`
* type: [COLOR_VALUE](../values/color_value.md)
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `FontColor`
* type: [COLOR_VALUE](../values/color_value.md)
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `LineColor`
* type: [COLOR_VALUE](../values/color_value.md)
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `Spare`
Leaving many spares for future mouse down/ mouse over colors and whatever else we want.
* type: number[]
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `barFontID`
Used in conjunction with barHeight.
* type: number
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `barHeight`
* type: [LENGTH_VALUE](../values/length_value.md)
* see:
[CDACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTIONBAREXT/)

### `type`
The signature type of the record.
* type: number
* value: 0xFF79
* see:
[SIG_CD_ACTIONBAREXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)
