# CSS Float Layout Bug

This repository demonstrates a subtle bug related to the use of the `float` property in CSS.  The bug manifests as unexpected layout behavior in some browsers, particularly when the parent element doesn't have its floats cleared properly. The `bug.css` file contains the problematic CSS, while `bugSolution.css` provides a solution.

This is a common problem when working with floats, highlighting the importance of understanding how the CSS layout engine handles floating elements and employing clearing techniques to avoid such issues.

## Reproducing the Bug

1. Clone this repository.
2. Open `index.html` (you will need to create a simple HTML file to test the CSS). 
3. Observe the layout in different browsers. You might see variations in how the floated elements are rendered.

## Solution

The solution, provided in `bugSolution.css`, involves using the `clear` property on a suitable element following the floated elements to ensure the layout is consistent across different browsers.