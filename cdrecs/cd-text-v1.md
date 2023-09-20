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

# CDTEXT

A
[CDTEXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDTEXT/).

## Examples
```yaml
type: 0xff85
FontID: 0x9010101
data: Basics
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `FontID`
Font ID
* type: number
* see:
[CDTEXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDTEXT/)

### `type`
The signature type of the record.
* type: number
* value: 0xFF85(`SIG_CD_TEXT`) or 0xFFE4(`SIG_CD_BIDI_TEXT`)
* see:
[SIG_CD_TEXT or SIG_CD_BIDI_TEXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)

## Optional properties

### `data`
The text content, if any.
* type: string
* see:
[CDTEXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDTEXT/)
