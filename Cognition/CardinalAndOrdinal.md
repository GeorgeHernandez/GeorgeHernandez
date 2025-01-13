# Cardinal and Ordinal

summary:: Cardinal counts, while ordinal orders.
parents:: [[Cognition]]

**Cardinal numbers** represent count or quantity. Its Latin root means "hinge".  

**Cardinality** is the number of elements in a set.  

E.g.
- If I have one shoe, then the cardinality is 1.    
- The set A = {1, 2, 3, 4} has a cardinality of 4.    
- The set B = {1, B, Δ, 2} has a cardinality of 4.

**Cardinality Requirements** specify the number of allowable elements in a set.
  
**Table:**: Cardinality requirements.

| English                     | Shorthand | Parentheses | Double Dot | Note                     |
| --------------------------- | --------- | ----------- | ---------- | ------------------------ |
| None                        | 0         | (0, 0)      | 0..0       |                          |
| None to One                 | 0 to 1    | (0, 1)      | 0..1       | RegEx: ?                 |
| None to N                   | 0 to N    | (0, N)      | 0..N       |                          |
| None or more                | 0 or more | (0, *)      | 0..*       | RegEx: *<br><br>  SQL: % |
| One<br><br>One and only one | 1         | (1, 1)      | 1..1       | RegEx: .<br><br>  SQL: _ |
| One to N                    | 1 to N    | (1..N)      | 1..N       |                          |
| One or more                 | 1 or more | (1, *)      | 1..*       | RegEx: +                 |
| M                           | M         | (M, M)      | M..M       |                          |
| M to N                      | M to N    | (M, N)      | M..N       |                          |
| M or more                   | M or more | (M, *)      | M..*       |                          |

E.g.
- Shoes. You can have no shoes, one shoe, or a pair of shoes.
  - None to two
  - 0 to 2
  - (0, 2)
  - 0..2
  - A complete pair of shoes: 2..2
  - 3 shoes is one too many!
  
An **ordinal number** indicates the position of an item in an ordered set. The word is related to "order".

  
**Table:** Ordinal numbers

| Spatial or chronological | Precedence or effect | Greek prefix        | Esapañol  |
| ------------------------ | -------------------- | ------------------- | --------- |
| first, 1st, 1º, 1ª       | primary              | proto-              | primero   |
| second, 2nd              | secondary            | deutero-            | segunda   |
| third, 3rd               | tertiary             | trito-              | tercero   |
| fourth, 4th              | quaternary, quartary | tetarto-            | cuarta    |
| fifth, 5th               | quinary              | (pempto-)           | quinto    |
| sixth, 6th               | senary               | (ecto-, hecto-)     | sexta     |
| seventh, 7th             | septenary            | (ebdomo-, hebdomo-) | séptimo   |
| eighth, 8th              | octonary             | (ogdo-)             | ocho      |
| ninth, 9th               | nonary               | (enato-)            | novena    |
| tenth, 10th              | decenary             | (decato-)           | décimo    |
| eleventh, 11th           | undenary             | (endecato-)         | décima    |
| twelfth, 12th            | duodenary            | (dodecato-)         | duodécimo |

  

Examples:
- Pat took 1st place.

While English uses the -st and -nd suffixes, some languages use an ordinal indicator after a number. Some fonts underline ordinal indicators.
- º for masculine items. Italian primo: 1º
- ª for feminine items.  Italian prima: 1ª
