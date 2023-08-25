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

# Item-Composite

An item with a value of composite data. Corresponds to
[TYPE_COMPOSITE](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/)

The `name` of the item must match the following regular expression:
```regex
/^[$](BODY|(V5)?ACTIONS)$/i
```
However, specs that inherit from this spec like
[Item-Composite-File](./item-composite-file-v1.md) specify their own, different,
name constraints.

All composite items with names that are not matched by any defined composite
spec are handled as [Item](./item-v1.md).

## Example

```yaml
name: $BODY
type: composite
signed: true
nonsummary: true
data:
  - type: 0x0081
  - type: 0x0083
        PABID: 1
      - type: 0xff85
        FontID: 0xa000001
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
An array of CDRecords.
* type: [CD](../cdrecs/cd-v1.md)[]

### `type`
The type of item.
* type: string
* value: "composite"
