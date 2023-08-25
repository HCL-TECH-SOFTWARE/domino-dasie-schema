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

# Item-Composite-File

An item with a value of a file as composite data. Corresponds to
[TYPE_COMPOSITE](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/)

The `name` of the item must match the following regular expression:
```regex
/^[$](ImageData|File(Data)?)$/i
```

The data for this file will be on the filesystem next to the note.
The name of the file (and also the note) will be one of the following item
values checked in order
1. `$Title`
1. `$FileNames`
1. `$ImageNames`

## Example

```yaml
name: $FileData
type: composite
signed: true
nonsummary: true
```

## Parent
[Item-Composite](./item-composite-v1.md)

## Inherited required properties
* [name](./item-v1.md#name)
* [type](./item-composite-v1.md#type)

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

