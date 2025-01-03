# Inconsistent Spacing in CSS Flexbox with min-width

This repository demonstrates a common issue with CSS flexbox and the `min-width` property.  When using `justify-content: space-between` with elements that have a `min-width`, the spacing between elements might become inconsistent, especially when the browser window is resized.  This is because the browser attempts to satisfy both `space-between` and the `min-width` constraint, sometimes leading to unexpected layout behavior.

The `bug.css` file shows the problematic code.  The `bugSolution.css` file provides a solution to ensure more consistent spacing.

This issue is relatively subtle and can be tricky to debug.  Understanding how flexbox handles `min-width` in conjunction with spacing properties is key to resolving it.