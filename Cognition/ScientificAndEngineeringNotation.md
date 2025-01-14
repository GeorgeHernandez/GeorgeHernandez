# Scientific and Engineering Notation

summary:: A few notes on scientific and engineering notation.
parents:: [[Cognition]]

Quantities and measurements of a **dimension** in science are often expressed as a **number (m)** and any applicable **units**. E.g.
- D = 3
  - D is a variable representing a Unitless Number. It is commonly called a Dimensionless Number, but that is not accurate since it still represents a concept.
  - It can be a unit vector, the number of macroscopic spatial dimensions, or any number of concepts.
- d = 3 m
  - d is a variable representing the Dimension (concept) of distance or length.
  - 3 is the Number (magnitude) of the Dimension.
  - m is the Unit of the Dimension.
- g = 9.8 m/s<sup>2</sup>
  - The typical gravity of earth expressed with units of m/s<sup>2</sup>.
  - The same measurement could also be expressed as 32 ft/s<sup>2</sup>.

Any real number can be written in the form *m*×10<sup>*n*</sup> in many ways. E.g. 350 can be written as:
- 3.5×10<sup>2</sup>
  - **Scientific notation** prefers to adjust the exponent n such that m is at least 1 but less than 10 (1 ≤ |m| < 10).
- 35×10<sup>1</sup>
- 350×10<sup>0</sup>
  - **Engineering notation** prefers to restrict the exponent n to 0 or multiples of 3 to better match with SI prefixes. Thus m will adjust such that m is at least 1 but less than 1000 (1 ≤ |m| < 1000).
  - Engineering notation is shorter and easier to type than scientific notation.
- 350E0
  - **E notation** expresses x10<sup>*n*</sup> as E*n* or e*n*. This is shorter and easier to type since it avoids superscripts.

**Table:** Different expressions of the same number.

| Example                | Note                                                           |
| ---------------------- | -------------------------------------------------------------- |
| 0.012                  |                                                                |
| 0.01 2                 | Spaces may be added for legibility in some contexts            |
| 1.2 ÷ 100              |                                                                |
| 1.2 / 100              |                                                                |
| 1.2 x 1/100            |                                                                |
| 1.2 x 1/10x10          |                                                                |
| 1.2 \* 1/10\*10        | Multiplication may be expressed with "\*" and other characters |
| 1.2 x 1/10<sup>2</sup> |                                                                |
| 1.2 x 10<sup>-2</sup>  | Scientific notation.                                           |
| 1.2E-2                 | Scientific notation with E notation.                           |
| 12 x 10<sup>-3</sup>   | Engineering notation. Aka ENG.                                 |
| 12e-3                  | Engineering notation using e notation.                         |

  

Both scientific and engineering notation may optionally show additional info about the accuracy of the number. E.g.
- 1 230 400
  - With no additional info this number may be exact or that it is precise up to the 4, i.e. it has 5 significant digits.
  - 1.2304e6
    - Using scientific or engineering notation explicitly states that this number has 5 significant digits.
- 1 inch ≝ 2.54 cm
  - 1 inch exactly equals 2.54 cm by definition.
  - Sometimes exactness must be explicitly stated for clarity.
- 1.672 621 923 69(51)e10−27 Kg
  - The mass of a Proton.
  - The above is equivalent to
    - (1.672 621 923 69±0.000 000 000 51)x10−27 Kg
  - Note that it is still unclear whether the error (5.1e−37 in this case) is the maximum possible error, standard error, or some other confidence interval.
