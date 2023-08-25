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

# Item-Formula

An item with a formula value. Corresponds to
[TYPE_FORMULA](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/).

## Examples
```yaml
name: MyFormulaItem
type: formula
data: SELECT @All
opaque: DEADBEEF
```

## Parent
[Item](./item-v1.md)

## Inherited required properties
* [name](./item-v1.md#name)

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

### `data`
The source of the formula.
* type: string

### `opaque`
The compiled formula as a base64 encoded string. This field is currently only
used for some fields that have their main section enclosed in other code.

*Note: Will likely be removed from future schema versions.*
* type: string

### `type`
The type of item.
* type: string
* value: "formula"
