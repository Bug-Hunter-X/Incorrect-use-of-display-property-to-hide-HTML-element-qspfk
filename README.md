# Incorrect Use of display Property in HTML

This repository demonstrates a common mistake when hiding HTML elements using JavaScript.  The `display: none;` style removes the element from the document flow, which can cause unexpected layout issues, especially when dealing with complex layouts or animations.  The correct way to hide an element is using the `visibility: hidden;` style, which maintains the element's space in the layout.

## Bug
The bug.html file shows an example where `display: none;` is used, resulting in incorrect behavior. The `bugSolution.html` shows the correct solution using `visibility: hidden;`.

## Solution
The solution involves switching from the `display` property to the `visibility` property. This maintains the element's space, preventing layout issues.