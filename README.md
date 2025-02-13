# Case-sensitive ID selection in HTML

This repository demonstrates a common mistake when selecting HTML elements by their ID using JavaScript's `getElementById` method.  The method is case-sensitive and does not correctly identify IDs with hyphens or other special characters unless the exact casing matches.

## Bug
The `bug.html` file shows the incorrect way to select an element with an id that has a hyphen using `document.getElementById()`.  The solution illustrates the corrected approach.