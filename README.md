# CSS `calc()` Inconsistency Bug

This repository demonstrates an uncommon bug related to the CSS `calc()` function.  The bug arises from inconsistent browser support for calculations involving percentages and lengths. This can cause unexpected rendering behavior across different browsers and versions.  The `bug.css` file contains the problematic code, while `bugSolution.css` provides a potential solution and explanation of the issue.

**Problem:** The use of `calc(50% - 10px)` may lead to unexpected or incorrect width calculation in older or less compatible browsers.  

**Solution:** We provide a workaround using alternative methods, such as media queries or JavaScript, to ensure consistent rendering across browsers.