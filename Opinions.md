# 1. My opinions

Here are some of my opinions to express myself in my own idiom and to maka a minor contribution to society. In short, I'm just muttering to myself on GitHub.

- [1. My opinions](#1-my-opinions)
    - [1.1. SHOULD](#11-should)
        - [1.1.1. Best](#111-best)
        - [1.1.2. Better](#112-better)
        - [1.1.3. Good](#113-good)
    - [1.2. SHOULD CSE](#12-should-cse)
        - [1.2.1. Best](#121-best)
        - [1.2.2. Better](#122-better)
        - [1.2.3. Good](#123-good)
    - [1.3. SHOULD NOT](#13-should-not)
    - [1.4. My opinions on opinions](#14-my-opinions-on-opinions)
        - [1.4.1. Bonus: Some quotes on facts & opinions](#141-bonus-some-quotes-on-facts--opinions)

## 1.1. SHOULD

### 1.1.1. Best

- Time and Date Standard: [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601), e.g. `YYYY-MM-DD hh:mm:ss` and `P3DT2H`. http://xkcd.com/1179/. I wonder if `2019\10\03-24` would have been better?
- System of Measurement: Metric. However I have a few personal opinions.
    - The prefixes for the positive exponents SHOULD change from:

        ```yaml
        [da, h, k, M, G,  T,  P,  E,  Z,  Y] to:
        [ D, H, K, M, G,  T,  P,  E,  Z,  Y]. e:
        [ 1, 2, 3, 6, 9, 12, 15, 18, 21, 24]
        ```

    - The prefixes for the negative exponents are fine. ISO 2955 was on track: µ isn't ASCII but it's easy to enter with a keyboard input like EN INTL.

        ```yaml
        [d, c, m, μ, n,  p,  f,  a,  z,  y]. e-:
        [1, 2, 3, 6, 9, 12, 15, 18, 21, 24]
        ```

- Browser: Google Chrome. Best by largest number of users and if you use multiple Google accounts. Chrome use less memory and have vertical tabbing.

### 1.1.2. Better

- Breastfeeding > Formula
- Toilet rolls releasing from the top > bottom
- A4 paper (ISO 216) > 8.5"x11"
- Common Era (CE) > AD
- Butter > Margarine
- Languages with few characters > 100s of characters
- LibreOffice > Open Office. LO can incorporate features from OO, but not the other way. LO has ~50x as many users.
- Renewable & Reusable > Single use
- Period (`.`) > Comma (`,`). For use as a decimal character, the period is simpler. It's right there on the numeric keypad.
- Wheelbarrow with centrally-mounted wheel > end-mounted wheel

### 1.1.3. Good

- Because of the [oligodynamic effect](https://en.wikipedia.org/wiki/Oligodynamic_effect), it would be nice if some germ-exposed items were made out of naturally biocidal metals. E.g. Brass doorknobs, silverware.
- The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED",  "MAY", and "OPTIONAL" MAY BE interpreted as described in [RFC 2119](http://www.ietf.org/rfc/rfc2119.txt). Aka Conformance Verbs for Requirement Levels.
- ISO 9000: 7 Quality Management Principles: Customer Focus. Leadership. Engagement of People. Process Approach. Improvement. Evidence-Based Decision Making. Relationship Management.
- 13 month calendars where each month is 28 day. E.g. [International Fixed Calendar](https://en.wikipedia.org/wiki/International_Fixed_Calendar) or [Positivist calendar](https://en.wikipedia.org/wiki/Positivist_calendar). Alas, not likely to ever be broadly implemented.

## 1.2. SHOULD CSE

### 1.2.1. Best

- Unicode Encoding: UTF-8, which is Windows Code Page Identifier 65001.
- Version Control: Git
- Indentation: 2 spaces, unless your system requires otherwise.
- Web Service: REST Web API

### 1.2.2. Better

- Floating Point Marker > Comma
- TOML > YAML > JSON > XML
- `!=` > `<>`
- 1 space between sentences > 2 spaces
- HTML > XHTML

### 1.2.3. Good

- The end of files (EOF) SHOULD have a blank line.
- Long versions of options for console commands SHOULD use a double dash, while the short versions use a single dash. E.g. `--force` and `-f`.
- The top of most of my HTML 5 documents SHOULD be: `<!DOCTYPE html><html lang="en"><head><meta charset="utf-8">`
- [Semantic Versioning](http://semver.org/) SHOULD be used. E.g.
    - `"foo": "1.8.7"`
        - `1`. MAJOR. Incompatible changes to the API.
        - `8`. MINOR. Backwards compatible additions to the API.
        - `7`. PATCH. Backwards compatible bug fixes.

## 1.3. SHOULD NOT

- Dibs. E.g. [Chicago's 'Dibs' Tradition Can Get Dirty, And Even Dangerous](https://www.npr.org/local/309/2020/03/02/811209907/chicago-s-dibs-tradition-can-get-dirty-and-even-dangerous).
- Graffiti on signs and homes
- Littering
- Jaywalking
- Low-waisted pants
- Not using turn signals
- Driving distracted, i.e. texting, doing social media, watching videos, etc.
- Firing guns into the air
- Loud music after midnight if your neighbors can hear it
- Anti: Vaccines, Round Earth, Evolution, Apollo Missions, Education & Science, Separation of church & state

## 1.4. My opinions on opinions

Your opinions and worldview will almost certainly differ from mine. And yet we have so much in common that it is important to be able to share and parse our opinions.

Policy affects many of us (the *polis*) and thus we need to make those decisions together, preferably using best practices, evidence, well formed logic, transparency, testing, perspective, etc., but also in an effective, timely, earnest, heard, woke, and emotionally conscious manner.

- LOGIC. Given the [is-ought problem](https://en.wikipedia.org/wiki/Is%E2%80%93ought_problem) and the [fact-value distinction](https://en.wikipedia.org/wiki/Fact%E2%80%93value_distinction), ought/value opinions may not be purely derived from facts or what-is. Even so we all form opinions. If however I present a proposition with a [formal fallacy](https://en.wikipedia.org/wiki/Formal_fallacy), then I apologize and should appreciate having it pointed out to me.
- FACTS. These should be reasonably independent of belief. The blur between [facts](https://en.wikipedia.org/wiki/Fact) and [opinions](https://en.wikipedia.org/wiki/Opinion) is astonishing. Is it possible to have all the facts? Do you know all the facts about your father? Education varies: Some people with no formal education may have a better set of facts; Two people can go to the same classes and come out with different facts. If my opinions are missing key facts, then I should appreciate being informed of the facts.
- EXPERIMENTS. The scientific method has been Man's best tool for coming up with positive facts. However it needs a creative hypothesis (i.e. an opinion) that can be tested. Similarly a person's character may just be bluster if never tested.
- DEFINITIONS. Some definitions are merely tautologies or language-games (Wittgenstein) and should be taken with a grain of salt. I may provide definitions that are convenient or context specific, and thus may vary from the vernacular or more proper definitions or standards. Definitions, like axioms, are in effect opinions upon which you build propositions or other opinions.
- EXPERIENCES. Anecdotal experiences are facts but like facts come in a great variety. Experiences can strongly color opinions and it is good to be aware of that.
- QUOTES. These are often succinct and witty, but also provide other perspectives, other opinions.
- HEURISTICS. While not optimal, perfect, or rational, heuristics are often satisfactory and are an opinion shared by many. I will strive to generate a small set of common sense, secular heuristics that can be used as axioms to apply broadly. Heuristics also come in a great variety. Heuristics, whether good or bad, sometimes become traditions.
- METAPHORS. Metaphors are great because they take something we already know and carry them forward to something else.
- PERSPECTIVE: Opinions vary in different points in our lives, contexts, etc.

### 1.4.1. Bonus: Some quotes on facts & opinions

"You can spend your whole life building a wall of facts between you and anything real." - Chuck Palahniuk

"The truth is more important than the facts." - Frank Lloyd Wright

"We do not deal much in facts when we are contemplating ourselves." - Mark Twain

"Few people are capable of expressing with equanimity opinions which differ from the prejudices of their social enviroment. Most people are incapable of forming such opinions." - Albert Einstein

'Experiment is the sole judge of scientific "truth".' - Richard Feynman

"Why, you simple creatures, the weakest of all weak things is a virtue which has not been tested in the fire." - Mark Twain
