# CSS Specificity Bug: Unexpected Behavior with !important and Inheritance

This repository demonstrates a subtle CSS bug related to specificity and the use of the `!important` declaration.  The bug arises from the unexpected interaction between inheritance, specificity, and `!important`, leading to styles not applying as intended.

## Bug Description
The core issue involves the unexpected outcome of CSS specificity when dealing with inheritance and `!important`.  A seemingly straightforward style application can produce surprising and inconsistent results due to the prioritization of declarations in specific scenarios.

## Reproduction
1. Clone this repository.
2. Open `bug.css` to review the problematic CSS code.
3. Create an HTML file (e.g., `index.html`) to test the styling using the structure below:
   ```html
   <div class="parent">
       <div class="child"></div>
   </div>
   ```
4. Link `bug.css` to your HTML file.
5. Observe the rendered color of the `.child` element.  It may not behave as intuitively expected.

## Solution
The solution is provided in `bugSolution.css`. The solution demonstrates a clear and straightforward fix to improve CSS code maintainability and avoid unexpected style issues.