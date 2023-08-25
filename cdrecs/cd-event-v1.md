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

# CDEVENT

A
[CDEVENT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENT/).

## Examples
```yaml
type: 0xfff9
ActionLength: 133
ActionType: 4
EventType: 1
Flags: 0x00000000
Reserved: AAAAAAAAAAAAAAAAAAA=
SignatureLength: 0
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `ActionLength`
Length of actions that follows.
* type: number
* see:
[CDEVENT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENT/)

### `ActionType`
One of
[ACTION_TYPE_xxx](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ACTION_TYPE_xxx/).
* type: number
* see:
[CDEVENT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENT/)

### `EventType`
One of
[HTML_EVENT_xxx](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/HTML_EVENT_xxx/).
* type: number
* see:
[CDEVENT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENT/)

### `Flags`
* type: number
* see:
[CDEVENT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENT/)

### `Reserved`
Base64 encoding of reserved data.
* type: string
* see:
[CDEVENT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDEVENT/)

### `type`
The signature type of the record.
* type: number
* value: 0xFFF9
* see:
[SIG_CD_EVENT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)
