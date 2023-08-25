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

# CDACTION(LotusScript)

A "run script"
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/).

## Examples
```yaml
type: 0xffbe
Flags: 0x0000019f
IconIndex: 0
ShareId: 0
Type: 2
data: |
  '++LotusScript Development Environment:2:5:(Options):0:66

  '++LotusScript Development Environment:2:5:(Forward):0:1
  Declare Sub Click(Source As Button)

  '++LotusScript Development Environment:2:5:(Declarations):0:2

  '++LotusScript Development Environment:2:2:BindEvents:1:129
  Private Sub BindEvents(Byval Objectname_ As String)
    Static Source As BUTTON
    Set Source = Bind(Objectname_)
    On Event Click From Source Call Click
  End Sub

  '++LotusScript Development Environment:2:2:Click:1:12
  Sub Click(Source As Button)
    Msgbox("foo")
  End Sub
title: lsaction
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
The LotusScript source for the action.
* type: string

### `Type`
Type of action (formula, script, etc.)
* type: number
* value: 2
* see:
[CDACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDACTION/)

