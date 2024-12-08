# CSS :hover Issue in Nested Flexbox

This repository demonstrates a subtle bug related to the `:hover` pseudo-class in CSS when dealing with nested elements within a flexbox container.  The issue is that the hover effect on the inner element is unexpectedly overridden by the hover effect on the parent.

The `bug.css` file contains the problematic CSS code, while `bugSolution.css` provides a corrected version.

## Problem

Hovering over the inner element does not trigger its defined hover effect, only the outer element's hover effect is applied. This occurs because of the way flexbox handles event propagation and potentially the specificity of CSS selectors.

## Solution

The solution involves understanding and adjusting the CSS selectors or using a different approach to avoid the conflict. The `bugSolution.css` file demonstrates a possible solution, offering a revised approach to ensure the inner element's hover state is properly handled.