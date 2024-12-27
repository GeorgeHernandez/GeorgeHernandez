# 1. Time Formatting

summary:: Time formatting for CSE.

- [1. Time Formatting](#1-time-formatting)
  - [1.1. Favorite Formatting Tokens](#11-favorite-formatting-tokens)
  - [1.2. Favorite Token Combinations](#12-favorite-token-combinations)
  - [1.3. References](#13-references)

## 1.1. Favorite Formatting Tokens

There are many tokens for formatting date and time in different contexts so you have to check your context. I am merely collecting a few of my favorites, especially ISO 8601.

- Year
  - `Y` or `y`. Right 1 digit of year. `0..9`.
  - `YY` or `yy` or `%y`. Right 2 digits of year. `00..99`.
  - `YYY` or `yyy`. Right 2 digits of year. `000..999`.
  - `YYYY` or `yyyy` or `%Y`. 4 digit year. Some contexts extend this to `+` or `-` and `0000..9999`.
  - `YYYYY` or `yyyyy`. 5 digit year.
- Period or Era
  - `g`. Period or era. E.g. `B.C.`.
- Month
  - `M`. 1 digit month. `1..12`.
  - `MM` or `%m`. 2 digit month. `01..12`.
  - `MMM` or `%b`. Abbreviated month name per locale. E.g. `Jan..Dec`.
  - `MMMM` or `%B`. Month name per locale. E.g. `January..December`.
- Week
  - `w`. 1 digit week of year per locale. `1..53`.
  - `ww` or `%U` or `%W`. 2 digit week of year per locale. `01..53`.
  - `W`. 1 digit week of month. `1..4`.
- Day of year
  - `%j`. 2 digit day of year. `001..0366`.
- Day of month
  - `D` or `d`. 1 digit day of month. `1..31`.
  - `DD` or or `dd` or `%d`. 2 digit day of month. `01..31`.
  - `Do`. 1 digit day of month with ordinal. `1st..31st`.
- Day of week
  - `e` or `%w`. Day of week per locale. `0..6`.
  - `eee` or `ddd` or `%a`. Day of week per locale. `Mon..Fri`.
  - `eeee` or `dddd` or `%A`. Day of week per locale. `Monday..Friday`.
- Hour
  - `%I`. 2 digit hour. `00..12`.
  - `HH` or `%H`. 2 digit hour. `00..23`, but `24` sometimes allowed.
- Minute
  - `mm` or `%M`. 2 digit minute. `00..59`.
- Second
  - `ss` or `%S`. 2 digit second. `00..59`.
- Subsecond
  - `.s` or `.f`. 1 digit E-1 seconds. `00..99`.
  - `.ss` or `.ff`. 2 digit E-2 seconds. `00..99`.
  - `.sss` or `.fff`. 3 digit E-3 seconds. `000..999`.
  - `.ssss` or `.ffff`. 4 digit E-4 seconds. `0000..9999`.
  - `.sssss` or `.fffff`. 5 digit E-5 seconds. `00000..99999`.
  - `.ssssss` or `.ffffff`. 6 digit E-6 seconds. `000000..999999`.
  - `.sssssss` or `.fffffff`. 7 digit E-7 seconds. `0000000..9999999`.
- Meridiem
  - `a` or `t`. Ante or post meidiem. Lowercase or 1 character. `a..p`.
  - `A` or `tt` or `%p`. Ante or post meidiem. Uppercase or 2 characters. `AM..PM`.
- Timezone
  - `Z` or `zzz`. Timezone offset as `+` or `-` and `HH:mm`. E.g. `-08:00`.
  - `%z`. Timezone offset as `+` or `-` and `HHMMSS`. E.g. `-080000`.
  - `z`. Timezone offset as `GMT ` and `+` or `-` and `HH:mm`. E.g. `GMT-08:00`.
  - `%Z`. Timezone name. E.g. `UTC`.
  - `zzzz`. Timezone offset. E.g. `Pacific Standard Time`.
- Timestamp
  - `X`. Unix timestamp in seconds.milliseconds. E.g. `1410715640.579`.
  - `x`. Unix timestamp in milliseconds. E.g. `1410715640579`.
- Etc
  - `Q`. Quarter. `1..4`.
  - `%%`. Literal `%`.
  - `\`. Escape character `%`. E.g. `h \h` can yield `1 h`.

## 1.2. Favorite Token Combinations

- Date
  - `YYYY-MM-DD`. ISO 8601 date. E.g. `2009-06-15`.
  - `MM/dd/yyyy` or`%d`. Short date per locale. E.g. `6/15/2009`.
  - `D`. Long date per locale. E.g. `Monday, June 15, 2009`.
- Date and time
  - `f`. Long date & short time per locale. E.g. `Monday, June 15, 2009 1:45 PM`.
  - `F`. Long date & long time per locale. E.g. `Monday, June 15, 2009 01:45:30 PM`.
  - `%c`. Medium date & medium time per locale. E.g. `Mon, June 15, 2009 01:45:30`.
  - `R`. RFC email dates (RFC 5322 / 2822 / 822 / 733). E.g. `Mon, 15 Jun 2009 13:45:30 GMT`.
- Time
  - `HH:mm`. ISO 8601 hour and minutes. E.g. `13:45`.
  - `HH:mm:ss` or `%X`1. ISO 8601 hour, minutes, and seconds. E.g. `13:45:30`.

## 1.3. References

- C/C++
  - https://en.wikipedia.org/wiki/C_date_and_time_functions
  - https://en.cppreference.com/w/c/chrono/strftime
- C#
  - https://learn.microsoft.com/en-us/dotnet/standard/base-types/standard-date-and-time-format-strings
  - https://learn.microsoft.com/en-us/dotnet/standard/base-types/custom-date-and-time-format-strings
- ISO 8601
  - https://en.wikipedia.org/wiki/ISO_8601
- Java
  - https://www.digitalocean.com/community/tutorials/java-simpledateformat-java-date-format
- JavaScript
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date
  - https://momentjs.com/docs/#/displaying/format/
- Python
  - https://docs.python.org/3/library/datetime.html
  - https://docs.python.org/3/library/datetime.html#strftime-strptime-behavior
- Etc
  - https://en.wikipedia.org/wiki/Date_and_time_notation
  - https://en.wikipedia.org/wiki/Date_and_time_representation_by_country
  - https://en.wikipedia.org/wiki/Time_formatting_and_storage_bugs
  - https://datatracker.ietf.org/doc/html/rfc822#section-5
