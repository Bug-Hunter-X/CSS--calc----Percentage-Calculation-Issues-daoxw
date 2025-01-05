# CSS `calc()` Percentage Calculation Issues

This repository demonstrates a common issue encountered when using the `calc()` function in CSS with percentage values. The problem arises from the browser's interpretation and resolution of percentages within the calculation, especially when the parent element's dimensions are dynamic or influenced by other factors.  The `bug.css` file shows the problematic code, and `bugSolution.css` provides a potential solution or workaround.

**Problem:** Inconsistent or unexpected results when using percentage values inside `calc()` in dynamic layouts.

**Solution:** Explore alternative approaches like using fixed values, viewport units (vw, vh), or adjusting the calculation logic to handle dynamic contexts more reliably.