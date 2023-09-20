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

# Item-Time-List

An item with an ordered list of time values. Corresponds to
[TYPE_TIME_RANGE](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/TYPE_xxx%20%5BTIME_RANGE%5D/).

## Examples
```yaml
name: MyTimeItem
type: time
data:
  - data: "2005-10-11T12:56:51.82-04:00"
    dst: true
  - data: "2005-10-12T12:56:51.82-04:00"
    dst: true
  - data: "2005-10-13T12:56:51.82-04:00"
    dst: true
signed: true
```

## Parent
[Item-Time](./item-time-v1.md)

## Inherited required properties
* [name](./item-v1.md#name)
* [type](./item-time-v1.md#type)

## Inherited optional properties
* [allday](./item-time-v1.md#allday)
* [anyday](./item-time-v1.md#anyday)
* [authors](./item-v1.md#authors)
* [dst](./item-time-v1.md#dst)
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
The list of times for the item.
* type: [`TIMEDATE`](../values/timedate.md)[]
