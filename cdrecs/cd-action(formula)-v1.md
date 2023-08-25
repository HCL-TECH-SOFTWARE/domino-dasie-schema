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

# CDACTION(Formula)

A "run script"
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/).

## Examples
```yaml
type: 0xffbe
Flags: 0x0000019f
IconIndex: 0
ShareId: 0
Type: 1
data: "@Prompt([Ok]; \"foo\";\"foo\")"
data_opaque: LgAAACIAAgANAAAAAAAAAAEAAwBmb28AAQADAGZvbwCwAwMABwAKAAMACTRTAA==
title: formulaaction
```

## Parent
[CDACTION](./cd-action-v1.md)


## Inherited required properties
* [type](./cd-action-v1.md#type)
* [Flags](./cd-action-v1.md#flags)
* [IconIndex](./cd-action-v1.md#iconindex)
* [ShareId](./cd-action-v1.md#shareid)

## Inherited optional properties
* [hidewhen](./cd-action-v1.md#hidewhen)
* [hidewhen_opaque](./cd-action-v1.md#hidewhen_opaque)

## Required properties

### `data`
The Formula source for the action.
* type: string

### `data_opaque`
A base64 encoding of the compiled formula.
* type: string
* Note: still evaluating if this is required.

### `Type`
Type of action (formula, script, etc.)
* type: number
* value: 1
* see:
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/)

