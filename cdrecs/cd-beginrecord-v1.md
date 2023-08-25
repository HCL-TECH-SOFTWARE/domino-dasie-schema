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
[CDBEGINRECORD](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBEGINRECORD/).

## Examples
```yaml
type: 0x00dd
Signature: 0xff8a
Version: 0
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `Signature`
[Signature](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)
of record begin is for.
* type: number
* see:
[CDBEGINRECORD](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBEGINRECORD/)

### `Version`
* type: number
* see:
[CDBEGINRECORD](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDBEGINRECORD/)

### `type`
The signature type of the record.
* type: number
* value: 0x00DD
* see:
[SIG_CD_BEGIN](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)
