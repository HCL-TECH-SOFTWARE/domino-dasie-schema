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

# About
This repository is a specification for the data format used by the **D**omino
**A**pplication **S**ource **I**mport/**E**xport (**dasie**) engine that's new
in HCL Notes Designer 14.0.0.

By providing this documentation in a source control repository, we hope to engage
the Domino developer community to work together to evolve the data format.

# Composite Schemas
Only the latest version of schemas will be listed here. Older schema versions
are (or will be) referenced by the latest version.

* [CD](./cdrecs/cd-v1.md)
* [CDACTION](./cdrecs/cd-action-v1.md)
* [CDACTION(Formula)](./cdrecs/cd-action(formula-v1).md)
* [CDACTION(LotusScript)](./cdrecs/cd-action(lotusscript)-v1.md)
* [CDACTIONBAR](./cdrecs/cd-actionbar-v1.md)
* [CDACTIONBAREXT](./cdrecs/cd-actionbarext-v1.md)
* [CDBEGINRECORD](./cdrecs/cd-beginrecord-v1.md)
* [CDBORDERINFO](./cdrecs/cd-borderinfo-v1.md)
* [CDCOLOR](./cdrecs/cd-color-v1.md)
* [CDENDRECORD](./cdrecs/cd-endrecord-v1.md)
* [CDEVENT](./cdrecs/cd-event-v1.md)
* [CDEVENTENTRY](./cdrecs/cd-evententry-v1.md)
* [CDIDNAME](./cdrecs/cd-idname-v1.md)
* [CDLSOBJECT](./cdrecs/cd-lsobject-v1.md)
* [CDPABDEFINITION](./cdrecs/cd-pabdefinition-v1.md)
* [CDPABHIDE](./cdrecs/cd-pabhide-v1.md)
* [CDPABREFERENCE](./cdrecs/cd-pabreference-v1.md)
* [CDSTYLENAME](./cdrecs/cd-stylename-v1.md)
* [CDTABLELABEL](./cdrecs/cd-tablelabel-v1.md)
* [CDTEXT](./cdrecs/cd-text-v1.md)

# Item Schemas
Only the latest version of schemas will be listed here. Older schema versions
are (or will be) referenced by the latest version.

* [Item](./items/item-v1.md)
* [Item-Action](./items/item-action-v1.md)
* [Item-Action-Java](./items/item-action-java-v1.md)
* [Item-Action-LotusScript](./items/item-action-lotusscript-v1.md)
* [Item-Composite](./items/item-composite-v1.md)
* [Item-Composite-File](./items/item-composite-file-v1.md)
* [Item-Formula](./items/item-formula-v1.md)
* [Item-IOU](./items/item-iou-v1.md)
* [Item-NoteLink-List](./items/item-notelink-list-v1.md)
* [Item-NoteRef-List](./items/item-noteref-list-v1.md)
* [Item-Number](./items/item-number-v1.md)
* [Item-Number-List](./items/item-number-list-v1.md)
* [Item-Number-Range](./items/item-number-range-v1.md)
* [Item-Object](./items/item-object-v1.md)
* [Item-Object-File](./items/item-object-file-v1.md)
* [Item-Text](./items/item-text-v1.md)
* [Item-Text-List](./items/item-text-list-v1.md)
* [Item-Time](./items/item-time-v1.md)
* [Item-Time-List](./items/item-time-list-v1.md)
* [Item-Time-Range](./items/item-time-range-v1.md)
* [Item-Unavailable](./items/item-unavailable-v1.md)

# Value Schemas
* [COLOR_VALUE](./values/color_value.md)
* [LENGTH_VALUE](./values/length_value.md)
* [TIMEDATE](./values/timedate.md)

# Type definitions
In this repository, there are references to "types" of data. Since the data
export format is a [YAML](https://yaml.org/) doc, most of these types map easily
over to a javascript type. For brevity, type information will be displayed in
[JSDoc type](https://jsdoc.app/tags-type.html) syntax.
