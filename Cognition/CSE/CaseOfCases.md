# Case of Cases

summary:: [Capitalization](https://en.wikipedia.org/wiki/Capitalization) and [letter case](https://en.wikipedia.org/wiki/Letter_case) for sets of words. 
parents:: [[CSE]]

Which capitalization style to use depends on context. E.g.

- Most English titles use [title case](https://en.wikipedia.org/wiki/Title_case).
- [Wikipedia titles are in sentence case]( Ghttps://en.wikipedia.org/wiki/Wikipedia:Article_titles#Article_title_format).
- There are many [programming naming conventions](https://en.wikipedia.org/wiki/Naming_convention_(programming)) depending on programming language and other contexts.

My preference is to have the name of the capitalization style also be an example of it.

## Vernacular Cases

This first set of capitalization styles is for space delimited words, ordered from all caps to no caps.

```text
Example                           Capitalization Style      Capitalize
======================================================================
THE BOOK AND BOB ARE IN THE CAR   ALL UPPER CASE            all letters
The Book And Bob Are In The Car   All Words Case            all words
The Book and Bob Are in the Car   Title Case                the first and all words with some exceptions †
The Book and Bob are in the Car   German  Sentence case     the first word and all        nouns
The book and Bob are in the car   English sentence case     the first word and all proper nouns & acroynyms
the book and Bob are in the Car   mid Sentence German case                     all        nouns
the book and Bob are in the car   mid sentence English case                    all proper nouns
the book and bob are in the car   all lower case
```

† The exceptions are usually:
- [Articles](https://en.wikipedia.org/wiki/Article_(grammar)). E.g. "the" or "an".
- [Adpositions](https://en.wikipedia.org/wiki/Adposition), especially prepositions and postpositions, e.g. "from now on".
- [Conjunctions](https://en.wikipedia.org/wiki/Grammatical_conjunction). E.g. "and".
- [Proper nouns](https://en.wikipedia.org/wiki/Proper_noun).

## Programming Cases

This second set of capitalization styles is in ASCII ascending order.

```text
Example     Capitalization Style
================================
tWo wOrDs   cAmEl aLtErNaTiNg sPaCe cAsE
two Words   camel Space Case
two words   lower space case
TwO WoRdS   PaScAl aLtErNaTiNg sPaCe cAsE
Two Words   Pascal Space Case
TWO WORDS   UPPER SPACE CASE, ALL CAPS
two_Words   camel_Snake_Case
two_words   lower_snake_case, snake_case
Two_Words   Pascal_Snake_Case
TWO_WORDS   UPPER_SNAKE_CASE, CONSTANT_CASE
two-Words   camel-KEBAB-CASE
two-words   lower-kebab-case, kebab-case
Two-Words   Pascal-Kebab-Case
TWO-WORDS   UPPER-KEBAB-CASE, COBOL-CASE
tWoWoRdS    cAmElAlTeRnAtInGcAsE
twoWords    camelCase
twowords    lowercase
TwOwOrDs    PaScAlAlTeRnAtInGcAsE
TwoWords    PascalCase
TWOWORDS    UPPERCASE, ALLCAPS
```

Acronyms get a bit odd. E.g. If you have "XML file", then do you treat it like an acronym or a word?

```text
In camelCase:  `xmlFile` or `xMLFile`?
In PascalCase: `XmlFile` or `XMLFile`.
```

## Other Cases

```text
GermanNounscase becauseGermanscapitalizeNouns
emoji🐱case Delimit🦋words🦋with🦋emojis
```
