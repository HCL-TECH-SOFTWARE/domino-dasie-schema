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

# Item

The simplest item is the item we do not support "stringifying" yet.

## Examples
```yaml
name: MyOpaqueItem
opaque: DEADBEEF
```

## Required properties

### `name`
The name of the item.
* type: string

### `opaque`
The base64 encoded binary data of the item.
* type: string

### `type`
The type of item
* type: string
* value: "opaque"

### `type_num`
The notes
[ITEM_TYPE](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/)
for this item.
* type: number

## Optional properties

### `authors`
Corresponds to [ITEM_READWRITERS](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ITEM_xxx/).
* type: boolean
* Default: false

### `encrypted`
Corresponds to [ITEM_SEAL](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ITEM_xxx/).
* type: boolean
* Default: false

### `link`
Item is a link to/from the object store.
* type: boolean
* Default: false

### `linked`
Item's value is stored in the object store.
  * type: boolean
  * Default: false

### `names`
Corresponds to [ITEM_NAMES](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ITEM_xxx/).
* type: boolean
* Default: false

### `nonsummary`
Corresponds to `not`([ITEM_SUMMARY](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ITEM_xxx/)).
* type: boolean
* Default: false
* *Note:* This is an intentional inversion of the item flag for summary so
  that we may omit it in the most common cases (item is summary).

### `ph`
Corresponds to [ITEM_PLACEHOLDER](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ITEM_xxx/).
* type: boolean
* Default: false

### `protected`
Corresponds to [ITEM_PROTECTED](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ITEM_xxx/).
* type: boolean
* Default: false

### `readers`
Corresponds to [ITEM_READERS](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ITEM_xxx/).
* type: boolean
* Default: false

### `signed`
Corresponds to [ITEM_SIGN](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ITEM_xxx/).
* type: boolean
* Default: false

### `version`
The version of the schema that the item conforms to.
* type: number
* Default: 1
