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

# CDPABHIDE

A
[CDPABHIDE](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABHIDE/).

## Examples
```yaml
type: 0xffbb
PABID: 0x0006
Reserverd: AAAm8JYKGPA=
data: "@True"
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `data`
The Formula source for the action.
* type: string

### `PABID`
ID number of the PAB being named.
* type: number
* see:
[CDPABHIDE](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABHIDE/)

### `Reserved`
Base64 encoding of reserved data.
* type: string
* see:
[CDPABHIDE](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABHIDE/)

### `type`
The signature type of the record.
* type: number
* value: 0xFFBB
