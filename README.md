# Uncommon CSS Specificity Bug: Unexpected Color Inheritance

This repository demonstrates a subtle bug related to CSS specificity and inheritance that can be difficult to debug. The issue arises when a more specific selector's styles unexpectedly override styles intended to be applied to a child element within a parent element.

## Bug Description

A CSS rule for a child element (e.g., `div p`) may not correctly override styles applied to its parent element (`div`) due to inheritance from another selector targeting that child element, causing unexpected styling inconsistencies.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the buggy code causing the problem.
3. Open `bugSolution.css` to see the correct implementation.
4. Observe the different behaviors using a browser's developer tools.