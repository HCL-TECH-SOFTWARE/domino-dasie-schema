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

# CDPABDEFINITION

A
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/).

## Examples
```yaml
type: 0xff82
FirstLineLeftMargin: 2160
Flags: 0x0c00
Flags2: 0x0094
JustifyMode: 0
LeftMargin: 4320
LineSpacing: 0
PABID: 1
ParagraphSpacingAfter: 1
ParagraphSpacingBefore: 0
RightMargin: 307
Tab:
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
  - 0
TabTypes: 0x00000000
Tabs: 0
data: []
```

## Parent
[CD](./cd-v1.md)

## Required properties

### `FirstLineLeftMargin`
Leftmost margin on first line (16 bits = about 44").
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `Flags`
Paragraph attribute flags -
[PABFLAG_xxx](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/PABFLAG_xxx/).
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `Flags2`
Extra paragraph attribute flags -
[PABFLAG2_xxx](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Symb/PABFLAG2_xxx/).
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `JustifyMode`
Paragraph justification type.
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `LeftMargin`
Leftmost margin, twips rel to abs left (16 bits = about 44").
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `LineSpacing`
(2*(Line Spacing-1)) (0:1,1:1.5,2:2,etc).
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `PABID`
ID of this PAB.
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `ParagraphSpacingAfter`
LineSpacing units below para.
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `ParagraphSpacingBefore`
LineSpacing units above para.
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `RightMargin`
Rightmost margin, twips rel to abs right (16 bits = about 44"). Special value
`0`` means right margin will be placed 1" from right edge of paper, regardless
of paper size.
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `Tab`
Table of tab stop positions, negative value means decimal tab.
* type: number[]
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `TabTypes`
2 bits per tab.
* type: number
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `Tabs`
Number of tab stops in table.
* type: number[]
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)

### `type`
The signature type of the record.
* type: number
* value: 0xFF82

# Optional properties

### `data`
Extra data that might trail the struct. (R5 margin extension, PABFLAG3)
* type: number[]
* see:
[CDPABDEFINITION](https://opensource.hcltechsw.com/domino-c-api-docs/reference/Data/CDPABDEFINITION/)
