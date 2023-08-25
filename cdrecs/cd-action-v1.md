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
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/)
with a `Type` (not `type`) that is not yet fully supported.

**Note**: According to the above link, JavaScript type actions have CDRecords
that trail this one containing the data of the script. We have not decided
yet if we want to collapse the records into 1 for the purposes of import/export.

Making that change would mean the CDRecord list indices would not necessarily
correlate with the actual indices in the item. There is not a 1:1 perfect
mapping today between a struct and the data schema here (for example, text
lengths are not necessary to preserve and can be reconstructed on import) but it
is pretty close. Doing this would diverge more substantially from the partiy
that currently exists.

Cutomer feedback would be appreciated.

## Examples
```yaml
type: 0xffbe
Flags: 0x0000019f
IconIndex: 0
ShareId: 0
Type: 3
opaque: EACBAoL/FgABAAAABwADAENvbW1lbnRmb28=
title: simpleaction
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `Flags`
Action flags
* type: number
* see:
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/)

### `IconIndex`
Index into array of icons.
* type: number
* see:
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/)

### `opaque`
The base64 encoded content of the action.
* type: string

### `ShareId`
Share ID of the Shared Action.
* type: number
* see:
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/)

### `Type`
Type of action (formula, script, etc).
* type: number
* see:
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/)

### `type`
The signature type of the record.
* type: number
* value: 0xFFBE
* see:
[SIG_CD_ACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/SIG_CD_xxx/)

## Optional properties

### `hidewhen`
The hide-when formula.
* type: string

### `hidewhen_opaque`
A base64 encoding of the compiled formula.
* type: string
* Note: still evaluating if this is required.
