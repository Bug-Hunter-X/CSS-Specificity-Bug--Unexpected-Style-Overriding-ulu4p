# CSS Specificity Bug

This repository demonstrates a common issue in CSS: unexpected style overriding due to selector specificity.  The bug showcases a scenario where a more specific selector unintentionally overrides a less specific one, resulting in unexpected visual behavior.

## Bug Description
The `bug.css` file contains CSS code that sets background colors for different elements.  However, due to the specificity of the selectors, the styles are not applied as expected. A more specific selector overrides a less specific one, leading to unexpected visual results.

## Solution
The `bugSolution.css` file provides a corrected version of the CSS, demonstrating how to resolve the specificity issue and achieve the intended styling.