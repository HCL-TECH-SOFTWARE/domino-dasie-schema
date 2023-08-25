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

# Item-Object

An item with an object value. Corresponds to
[TYPE_OBJECT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/).

## Examples

```yaml
name: MyObjectItem
obj_type: 0x0008
obj_class: 0x0001
obj_privs: 0x0000
opaque: DEADBEEF
```

## Parent
[Item](./item-v1.md)

## Inherited required properties
* [name](./item-v1.md#name)
* [opaque](./item-v1.md#opaque)

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

### `obj_class`
The class of the object.
* type: number

### `obj_privs`
The privilages of the object.
* type: number

### `obj_type`
The type of the object.
* type: number

### `type`
The type of item.
* type: string
* value: "object"

## Optional properties

### `item_extra_opaque`
A base64 encoding of the extra data (if any) at the end of the
[OBJECT_DESCRIPTOR](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/OBJECT_DESCRIPTOR/).
* type: string
