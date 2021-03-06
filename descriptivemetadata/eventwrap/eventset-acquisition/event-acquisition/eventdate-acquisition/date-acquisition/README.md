---
description: Date
---

# date \[Acquisition]

### Description

#### LIDO

Contains a date specification by providing a set of years as earliest and latest date delimiting the respective span of time. This may be a period or a set of years in the proleptic Gregorian calendar delimiting the span of time. If it is an exact date, possibly with time, repeat the same date (and time) in earliest and latest date.

#### MNHA

This element contains the following elements:

* `earliestDate`
* `latestDate`

### Attributes

_This element does not have attributes._

### Example

```markup
 <lido:date>
     <lido:earliestDate>#Acquisition date ISO 8601#</lido:earliestDate>
     <lido:latestDate>#Acquisition date ISO 8601#</lido:latestDate>
 </lido:date>
```
