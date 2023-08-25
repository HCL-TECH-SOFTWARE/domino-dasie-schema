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

# Item-Object-File

An item with an object value that is a file. Corresponds to
[TYPE_OBJECT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx/).

## Examples

```yaml
name: MyObjectFileItem
type: object
obj_type: 0x0000
obj_class: 0x0200
obj_privs: 0x0000
file_name: "%%source%%.jar"
HostType: 0
CompressionType: 0
FileAttributes: 0
Flags: 0x0001
FileCreated:
  data: "2023-08-28T10:27:11.56-04:00"
  dst: true
FileModified:
  data: "2023-08-28T10:27:11.56-04:00"
  dst: true
opaque: |
  UEsDBBQACAgIAGVTHFcAAAAAAAAAAAAAAAAOAAAASmF2YUFnZW50LmphdmFVjrGOwkAMRHsk/mHK5Irw
  AYgCTjRIdw00lGZjhdWFdbR2EAjl30miAHsuvJ7VG3v8pZFoqMVaLUq5+CDF13I+m8+a9lR7B1eTKnZ0
  pXXFwcA341AqRrUhZTwGGn1Njqv4Er9irD/kQ5Z/AMDifZB4155VvQTo9K5QsU2fWb5M0fHitwTrI4BS
  sXrZi96cYuOGdMdigewobYSTklEJK84cOf9QHRyZO2fbm+PGhkic/4/MRRN9sL2R+ztEcpzm7Map790T
  UEsHCLO9HTDEAAAAWgEAAFBLAQIUABQACAgIAGVTHFezvR0wxAAAAFoBAAAOAAAAAAAAAAAAAAAAAAAA
  AABKYXZhQWdlbnQuamF2YVBLBQYAAAAAAQABADwAAAAAAQAAAAA=
signed: true
encrypted: true
```

## Parent
[Item-Object](./item-object-v1.md)

## Inherited required properties
* [name](./item-v1.md#name)
* [obj_class](./item-object-v1.md#obj_class)
* [obj_privs](./item-object-v1.md#obj_privs)
* [obj_type](./item-object-v1.md#obj_type)
* [opaque](./item-v1.md#opaque)
* [type](./item-object-v1.md#type)

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


### `CompressionType`
The type of compression used to store the file.
* type: number
* see: [FILEOBJECT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/FILEOBJECT/)

### `file_name`
The name of the file.
* type: string

### `FileAttributes`
Original file attributes.
[ATTRIB_xxx](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/ATTRIB_xxx/)
* type: number
* see:
  [FILEOBJECT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/FILEOBJECT/)

### `FileCreated`
Original file date/time of creation.
* type: [`Item-Time`](./item-time-v1.md#optional-properties)
* Note: The object value **only** contains optional properties defined for
[Item-Time](./item-time-v1.md#optional-properties).

### `FileModified`
Original file date/time of modification.
* type: [`Item-Time`](./item-time-v1.md#optional-properties)
* Note: The object value **only** contains optional properties defined for
[Item-Time](./item-time-v1.md#optional-properties).

### `Flags`
Miscellaneous flags.
[FILEFLAG_xxx](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/FILEFLAG_xxx/)
* type: number
* see:
  [FILEOBJECT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/FILEOBJECT/)

### `HostType`
Text delimiters.
[HOST_xxx](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/HOST_xxx)
* type: number
* see:
  [FILEOBJECT](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/FILEOBJECT/)

