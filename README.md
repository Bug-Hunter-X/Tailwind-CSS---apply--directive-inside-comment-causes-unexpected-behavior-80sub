# Tailwind CSS `@apply` directive inside comment causes unexpected behavior

This repository demonstrates an unexpected behavior in Tailwind CSS when using the `@apply` directive inside a comment.  The `@apply` directive should be used within a class definition to apply pre-defined utility classes, but placing it in a comment block still impacts the generated CSS unexpectedly.

## Steps to reproduce

1. Include the provided `bug.js` file in your project.
2. Compile your Tailwind CSS.
3. Observe that unexpected CSS is generated due to the `@apply` directive inside the comment.

## Solution

The solution (`bugSolution.js`) shows the correct way to use the `@apply` directive to ensure that only the intended classes are applied.