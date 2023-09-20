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

# TIMEDATE

A
[TIMEDATE](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/TIMEDATE/).

## Example
```yaml
dst: true
data: "2005-10-11T12:56:51.82-04:00"
```

## Optional properties

### `allday`
If the represented time is date-only.
* type: boolean
* Default: false

### `anyday`
If the represented time is time-only.
* type: boolean
* Default: false

### `data`
The time value of the field (if any) in
[rfc3339](https://datatracker.ietf.org/doc/html/rfc3339) format.
* type: string
* Default: empty

### `dst`
If the represented time is/was in DST.
* type: boolean
* Default: false
