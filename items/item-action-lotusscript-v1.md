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

# Item-Action-LotusScript

An item with an action. Corresponds to
[TYPE_ACTION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/).

This item has a `code_type` that identifies it as containing lotusscript.

## Examples
```yaml
name: MyLSActionItem
type: action
code_type: 65413
data: |
  '++LotusScript Development Environment:2:5:(Options):0:74
  Option Public
  Option Declare
```

## Parent
[Item-Action](./item-v1.md)

## Inherited required properties
* [code_type](./item-action-v1.md#code_type)
* [name](./item-v1.md#name)
* [type](./item-action-v1.md#type)

## Inherited optional properties
* [authors](./item-v1.md#authors)
* [encrypted](./item-v1.md#encrypted)
* [link](./item-v1.md#link)
* [linked](./item-v1.md#linked)
* [names](./item-v1.md#names)
* [nonsummary](./item-v1.md#nonsummary)
* [ph](./item-v1.md#ph)
* [protected](./item-v1.md#protected)
* [readers](./item-v1.md#readers)
* [signed](./item-v1.md#signed)
* [version](./item-v1.md#version)

## Required properties

### `code_type`
The type of action.
* type: number
* value: 65413

### `data`
The lotusscript source for the action.
* type: string

### `dwFlags`
Action flags.
* type: number
