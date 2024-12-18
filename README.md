# Tailwind CSS @apply Directive Style Override Issue

This repository demonstrates a common issue encountered when using Tailwind CSS's `@apply` directive. The problem arises when styles applied via `@apply` are overridden by other styles within the same class.  This doesn't throw an error, but leads to incorrect styling.

The `bug.css` file shows the problematic code. `bugSolution.css` demonstrates how to resolve the issue by restructuring the CSS to avoid style conflicts.

## Steps to Reproduce

1. Clone the repository.
2. Open `bug.html` in your browser (you will need to create a simple HTML file to test).
3. Observe the unexpected styling. 
4. Compare to the correctly rendered styles in `bugSolution.html` (also needs creation).

## Solution

Refer to `bugSolution.css` for a corrected implementation.  The key is to avoid conflicting styles within the same class. Carefully consider the order of styles and avoid unnecessary overrides.