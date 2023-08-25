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

# Item-IOU

An item with type corresponding to
[TYPE_INVALID_OR_UNKNOWN](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/).

## Examples
```yaml
name: MyIOUItem
type_num: 0
nonsummary: true
ph: true
```

## Inherited required properties
* [name](./item-v1.md#name)
* [type_num](./item-v1.md#type_num)

## Inherited optional properties
* [authors](./item-v1.md#authors)
* [encrypted](./item-v1.md#encrypted)
* [link](./item-v1.md#link)
* [linked](./item-v1.md#linked)
* [names](./item-v1.md#names)
* [nonsummary](./item-v1.md#nonsummary)
* [opaque](./item-v1.md#opaque)
* [ph](./item-v1.md#ph)
* [protected](./item-v1.md#protected)
* [readers](./item-v1.md#readers)
* [signed](./item-v1.md#signed)
* [version](./item-v1.md#version)

## Required properties

### `type`
The type of item.
* type: string
* value: "iou"
