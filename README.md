
# cf-wk03-ex1-10 :computer

## 1- Issues with deployment (GitHub Pages)

- Absolute vs relative path for some pages needed to be corrected.
- Using xml stylesheet tag inside SVG file to format SVG as an object instead og img or SVG tags (style sheet path requires exit from img folder "../" at the begining).

## 2- Issues with cross testing (BitBar)

- Grid dose not work on IE11 (will not be fixed, IE is used 0.71% in germany <https://gs.statcounter.com/browser-market-share/desktop/germany/#monthly-202207-202207-bar>)
- Navigation is not completly visible on mobile (**fixed**: flex-wrap).
- Some buttons changes look based on OS (**fixed**: Changed input to button).
- svg has overflow on mobile (**fixed**: max-width 90%).

## 3- IDE & linters

- VsCode + W3C Web Validator.

## 4- Screenshot of W3C Validator

![W3C Valitator](img/Screenshot%202022-08-18%20011617.png)
