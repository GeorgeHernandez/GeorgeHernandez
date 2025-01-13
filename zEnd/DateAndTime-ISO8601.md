# Date and Time: ISO 8601

summary:: ISO 8601 is an international standard covering the worldwide exchange and communication of date and time-related data.
parents:: [[zEnd]]

**ISO 8601** is an international standard covering the worldwide exchange and communication of date and time-related data. It is maintained by the International Organization for Standardization (ISO) and was first published in 1988, with updates in 1991, 2000, 2004, and 2019, and an amendment in 2022.

The standard provides a well-defined, unambiguous method of representing calendar dates and times in worldwide communications, especially to avoid misinterpreting numeric dates and times when such data is transferred between countries with different conventions for writing numeric dates and times.

Key Principles:
- Date and time values are ordered from the largest to smallest unit of time: year, month (or week), day, hour, minute, second, and fraction of second. The lexicographical order of the representation thus corresponds to chronological order, except for date representations involving negative years or time offset. This allows dates to be naturally sorted by, for example, file systems.
- Each date and time value has a fixed number of digits that must be padded with leading zeros.  

**Table:** ISO  8601 examples.

| Syntax               | Example          |
| -------------------- | ---------------- |
| YYYY-MM-DD           | 2024-11-05       |
| YYYY-MM              | 2024-11          |
| hh:mm:ss             | 13:47:30         |
| hh:mm                | 13:47            |
| YYYY-MM-DDThh:mm     | 2024-11-05T13:47 |
| PnYnMnDTnHnMnS       | P3Y3D            |
| `P<date>T<time>`     | P1               |
| `P<date>`            |                  |
| `PT<time>`           |                  |
| `<start>/<end>`      | 2024-11/12       |
| `<start>/<duration>` | 13:47/PT30M      |

 ## References:

- [https://en.wikipedia.org/wiki/ISO_8601](https://en.wikipedia.org/wiki/ISO_8601)     
- [https://xkcd.com/1179/](https://xkcd.com/1179/)
  - [https://www.explainxkcd.com/wiki/index.php/1179:_ISO_8601](https://www.explainxkcd.com/wiki/index.php/1179:_ISO_8601)<br>![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXep66RWsxuoO10-26s7SbTrcE4ArZIjlqF_k4Egc4g4Fm58Ea6QctK88E5HVeLSEL0MVPM2MDQRmIPV9N92uW2R40wB4j0SFKmy4NIXEuwcnhjGo1oe0rKsV-j_N3nqonW1tsNa38t6Smnb0B-hgyLCi_g?key=MzrU6AGm-3c4r06Eg7oiQx2Z)