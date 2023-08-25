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

# CDBEGINRECORD

A
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/).

## Examples
```yaml
type: 0xfffc
BorderFlags: 0
BorderStyle: 0
BorderWidthBottom: 0
BorderWidthLeft: 0
BorderWidthRight: 0
BorderWidthTop: 0
Color:
  Flags: 0x0001
  rgb: 0x000000
DropShadowWidth: 0
Flags: 0x00000000
InnerWidthBottom: 0
InnerWidthLeft: 0
InnerWidthRight: 0
InnerWidthTop: 0
OuterWidthBottom: 5
OuterWidthLeft: 0
OuterWidthRight: 0
OuterWidthTop: 0
dwSpare: 0x00000000
wSpares:
  - 0x0000
  - 0x0000
  - 0x0000
  - 0x0000
  - 0x0000
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `BorderFlags`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `BorderStyle`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `BorderWidthBottom`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `BorderWidthLeft`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `BorderWidthRight`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `BorderWidthTop`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `Color`
* type: [COLOR_VALUE](../values/color_value.md)
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `DropShadowWidth`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `Flags`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `InnerWidthBottom`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `InnerWidthLeft`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `InnerWidthRight`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `InnerWidthTop`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `OuterWidthBottom`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `OuterWidthLeft`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `OuterWidthRight`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `OuterWidthTop`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `dwSpare`
* type: number
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `wSpares`
* type: number[]
* see:
[CDBORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBORDERINFO/)

### `type`
The signature type of the record.
* type: number
* value: 0xFFFC
* see:
[SIG_CD_BORDERINFO](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)
