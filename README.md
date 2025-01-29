# Unexpected rendering due to invalid CSS property

This repository demonstrates an uncommon CSS error related to the `font-size-adjust` property. The issue arises from using an invalid value for this property, leading to unpredictable rendering results across different browsers.

## Bug Description

The `font-size-adjust` property, while valid, is not widely supported and its behavior can be inconsistent. Setting it to an invalid value like `0.5` (as shown in the example) can lead to the property being ignored or causing unexpected layout changes.

## Solution

The best solution is to remove the `font-size-adjust` property entirely unless you have a specific and well-understood reason to use it and have thoroughly tested it across various browsers.  For most use-cases, this property is unnecessary.

## How to reproduce the bug

1. Copy and paste the code from `bug.css` into a stylesheet.
2. Apply this stylesheet to some HTML elements.
3. Observe the rendering behavior, especially differences across browsers, compared to the expected behaviour in `solution.css`