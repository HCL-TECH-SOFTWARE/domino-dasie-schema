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

# Item-Text

An item with a text value. Corresponds to
[TYPE_TEXT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/).

## Examples

### Simple string value
```yaml
name: MyTextItem
type: text
data: The quick brown fox jumps over the lazy dog.
```

### Multi-line string value
```yaml
name: MyTextItem
type: text
data: |
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
  quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
  consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
  cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
  non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
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
The value of the text item.
* type: string

### `type`
The type of item.
* type: string
* value: "text"
