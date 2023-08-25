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

# Item-NoteRef-List

An item with a list of unids as a value. Corresponds to
[TYPE_NOTEREF_LIST](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx%20%5BNOTEREF_LIST%5D/).

## Example

```yaml
name: MyNoteRefListItem
type: noteref
data:
  - OF1B8B0F20B0B86D23-ON004F6DC400258A19
  - OF1B8B0F20B0B86D23-ON004F6DC400258A12
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
The list of unids.
* type: string[]

### `type`
The type of item.
* type: string
* value: "noteref"
