# Brownie Calculator

A basic calculator built with HTML, CSS, and JavaScript, styled around a butter yellow and vintage brown color palette inspired by a Pantone-style mood board.

## Features

- **Arithmetic operations**: addition (+), subtraction (−), multiplication (×), division (÷)
- **Additional functions**: percent (%), sign toggle (±), clear (AC)
- **Live display**: shows the running expression and result in real time
- **Error handling**: displays "Error" on divide-by-zero instead of breaking
- **Keyboard support**:
  - `0–9` : enter digits
  - `.` : decimal point
  - `+ - * /` : operators
  - `Enter` or `=` : evaluate
  - `Backspace` : delete last digit
  - `Esc` : clear all
  - `%` : percent
- **Responsive design**: works on desktop and mobile screen sizes
- **Accessible**: visible keyboard focus states, respects reduced-motion preferences

## Tech Stack

- **HTML** : structure/markup
- **CSS** : all styling is internal (inline `<style>` block, no external stylesheet)
- **JavaScript** : all logic is internal (inline `<script>` block, no external script file)
- **Google Fonts** (Fraunces, Space Grotesk, Space Mono) - loaded via CDN link; requires an internet connection to display the intended fonts, but the calculator still functions without it (falls back to system fonts)

Everything is contained in a single file: `index.html`. No build tools, dependencies, or installation required.

## Design Notes

- **Palette**: butter yellow (`#EAD98B`, `#F5E9BE`) paired with vintage browns (`#2E2117`, `#5A4130`), with a mustard-gold accent (`#B98A2E`) for the active operator and equals button
- **Display**: styled like a Pantone swatch card, with a butter/brown color-chip strip above the numeric readout
- **Typography**: Fraunces (serif) for the result display, Space Grotesk for buttons/UI, Space Mono for labels

## File Structure

```
index.html                     # complete calculator (HTML + CSS + JS in one file)
README.md                      # this file
```
