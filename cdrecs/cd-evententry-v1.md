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

# CDEVENTENTRY

A
[CDEVENTENTRY](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENTENTRY/).

## Examples
```yaml
type: 0xff5f
dwReserved: 0x00000000
wActionType: 1
wEventId: 213
wPlatform: 1
wReserved: 0
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `dwReserved`
Future use.
* type: number
* see:
[CDEVENTENTRY](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENTENTRY/)

### `wActionType`
Action type (the language... LotusScript, Javascript, Formula, etc.).
* type: number
* see:
[CDEVENTENTRY](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENTENTRY/)

### `wEventId`
Event id. The event that this will run on... OnClick, Exit, etc.
* type: number
* see:
[CDEVENTENTRY](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENTENTRY/)

### `wPlatform`
Platform type.
* type: number
* see:
[CDEVENTENTRY](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENTENTRY/)

### `wReserved`
Future use.
* type: number
* see:
[CDEVENTENTRY](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENTENTRY/)

### `type`
The signature type of the record.
* type: number
* value: 0xFF5F
* see:
[SIG_CD_EVENT_LANGUAGE_ENTRY](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)
