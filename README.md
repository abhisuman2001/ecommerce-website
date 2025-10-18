# Simple Calculator

## Overview
A clean, single-file web calculator that performs the four basic arithmetic operations: addition, subtraction, multiplication, and division. It features a responsive layout, keyboard support, and user-friendly interactions such as clear, backspace, and sign toggle. No build steps or dependencies—just open and use.

Key features:
- +, −, ×, ÷, equals, clear (AC), backspace, and ±
- Keyboard input: 0–9, + − × /, ., Enter/=/Esc/Backspace
- Graceful handling of division by zero (displays Error)
- Precision rounded to 12 significant digits to reduce floating-point noise
- Accessible roles and live region updates

## Setup
- Option 1: Double-click index.html to open it in any modern browser.
- Option 2: Serve it locally with any static server (optional).
  - Python 3: python -m http.server 8000
  - Node (http-server): npx http-server

No installation or build steps required.

## Usage
- Click buttons or use your keyboard:
  - Digits: 0–9
  - Decimal: .
  - Operators: +, -, *, /
  - Evaluate: Enter or =
  - Clear: Esc (or AC button)
  - Backspace: Backspace key (or ⌫ button)
  - Toggle sign: ±
- Expression preview appears above the main display.
- On division by zero, “Error” is shown; press any digit or AC to continue.

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.