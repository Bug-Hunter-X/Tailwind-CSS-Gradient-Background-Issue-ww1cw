# Tailwind CSS Gradient Background Issue

This repository demonstrates a potential issue with Tailwind CSS gradient backgrounds.  Some older browsers may not support the `bg-gradient-to-r` utility, leading to incorrect rendering or no rendering at all. This repository provides a code example demonstrating the issue and a potential solution.

## Bug

The `bug.js` file contains a simple example of a Tailwind CSS gradient background. The expected output is a div with a smooth gradient from blue to purple. However, in some older browsers or devices, the gradient may not render correctly, or may appear as a solid color.

## Solution

The `bugSolution.js` file provides a potential solution by using a fallback mechanism.  This utilizes a linear-gradient for broader browser support.

## How to reproduce

1. Clone this repository.
2. Open the `bug.html` in an older browser to see the issue.
3. Compare the results with a modern browser.
