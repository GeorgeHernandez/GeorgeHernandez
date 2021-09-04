# 1. My opinions

On this page I'm sharing some of my opinions to express myself and maka a minor contribution to society.

I'm not here to write long elaborate manifestos about everything, but rather to make short expressive statements on select subjects.

I'm not here to totally change the world. I'm not doing a sophisticated coordinated campaign utilizing every social media platform. Rather I'm just muttering to myself on GitHub.

- [1. My opinions](#1-my-opinions)
  - [1.1. SHOULD](#11-should)
    - [1.1.1. Best](#111-best)
    - [1.1.2. Better](#112-better)
    - [1.1.3. Good](#113-good)
  - [1.2. SHOULD CSE](#12-should-cse)
    - [1.2.1. Best](#121-best)
    - [Better](#better)
    - [Good](#good)

## 1.1. SHOULD

### 1.1.1. Best

- Time and Date Standard: [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601): YYYY-MM-DD hh:mm:ss. http://xkcd.com/1179/. I wonder if 2019\10\03-24 would have been better?
- System of Measurement: Metric. However I have a few personal opinions.
    - The prefixes for the positive exponents SHOULD change from:
        - `[da, h, k, M, G,  T,  P,  E,  Z,  Y] to:`
        - `[ D, H, K, M, G,  T,  P,  E,  Z,  Y]. e:`
        - `[ 1, 2, 3, 6, 9, 12, 15, 18, 21, 24]`
    - The prefixes for the negative exponents are fine:
        - `[d, c, m, μ, n,  p,  f,  a,  z,  y]. e-:`
        - `[1, 2, 3, 6, 9, 12, 15, 18, 21, 24]`
        - ISO 2955 was on track: µ isn't ASCII but it's easy to enter with a keyboard input like EN INTL.

### 1.1.2. Better

- Breastfeeding > Formula
- Toilet rolls releasing from the top > bottom
- A4 paper (ISO 216) > 8.5"x11"
- Common Era (CE) > AD
- Butter > Margarine
- Languages with few characters > 100s of characters
- LibreOffice > Open Office. LO can incorporate features from OO, but not the other way. LO has ~50x as many users.
- Renewable & Reusable > Single use
- Period (.) > Comma (,). For use as a decimal character, the period is simpler.
- Wheelbarrow with centrally-mounted wheel > end-mounted wheel

### 1.1.3. Good

- Because of the oligodynamic effect (https://en.wikipedia.org/wiki/Oligodynamic_effect), it would be nice if some germ-exposed items were made out of naturally biocidal metals. E.g. Brass doorknobs, silverware.
- The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED",  "MAY", and "OPTIONAL" MAY BE interpreted as described in RFC 2119 [http://www.ietf.org/rfc/rfc2119.txt]. Aka Conformance Verbs for Requirement Levels.
- ISO 9000: 7 Quality Management Principles: Customer Focus. Leadership. Engagement of People. Process Approach. Improvement. Evidence-Based Decision Making. Relationship Management.
- 13 month calendars where each month is 28 day. E.g. https://en.wikipedia.org/wiki/International_Fixed_Calendar or https://en.wikipedia.org/wiki/Positivist_calendar. Alas, not likely. to ever be broadly implemented.

## 1.2. SHOULD CSE

### 1.2.1. Best

- Unicode Encoding: UTF-8, which is Windows Code Page Identifier 65001.
- Version Control: Git
- Browser: Google Chrome
- Indentation: 2 spaces, unless your system requires otherwise.
- Web Service: REST Web API

### Better

- Floating Point Marker > Comma
- TOML > YAML > JSON > XML
- != > <>
- 1 space between sentences > 2 spaces
- HTML > XHTML

### Good

- EOF SHOULD have a blank line
- Long versions of options for console commands SHOULD use a double dash, while the short versions use a single dash. E.g. --force and -f.
- The top of HTML 5 SHOULD be:
    - `<!DOCTYPE html><html lang="en"><head><meta charset="utf-8">`
    - In Pug/Jade:
        - `doctype html`
        - `html(lang="en")`
            - `head`
                - `meta(charset="utf-i")`
- Semantic Versioning (http://semver.org/) SHOULD be used. E.g.
    - "foo": "1.8.7"
        - 1. MAJOR. Incompatible changes to the API.
        - 8. MINOR. Backwards compatible additions to the API.
        - 7. PATCH. Backwards compatible bug fixes.
