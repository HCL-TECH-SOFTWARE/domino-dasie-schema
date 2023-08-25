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

# CDIDNAME

A
[CDIDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDIDNAME/).

## Examples
```yaml
type: 0xff7a
Class: TableSpacing
ID: Server_Transact_1_1_1
reserved: AAAAAAAAAAAAAA==
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `reserved`
Base64 encoding of the `reserved` struct record.
* type: string
* see:
[CDIDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDIDNAME/)

### `type`
The signature type of the record.
* type: number
* value: 0xFF7A
* see:
[SIG_CD_IDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)

## Optional properties

### `Class`
* type: string
* see:
[CDIDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDIDNAME/)

### `Extra`
Extra attribute/value pairs.
* type: string
* see:
[CDIDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDIDNAME/)

### `ID`
* type: string
* see:
[CDIDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDIDNAME/)

### `Name`
* type: string
* see:
[CDIDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDIDNAME/)

### `Style`
* type: string
* see:
[CDIDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDIDNAME/)

### `Title`
* type: string
* see:
[CDIDNAME](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDIDNAME/)
