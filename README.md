# Uncommon HTML Error: Typo in Element ID

This repository demonstrates a subtle HTML/JavaScript error that can be challenging to debug. The bug involves a simple typo in an element's ID, causing the `getElementById` method to fail silently in some browsers.

## Bug Description

The `bug.html` file contains a typo in the ID attribute of a div element.  The JavaScript code attempts to access this element using the incorrect ID, leading to a runtime error.

## Bug Solution

The `bugSolution.html` file corrects the typo in the ID attribute. Now the JavaScript code correctly accesses and modifies the content of the div element.

## How to Reproduce

1. Open `bug.html` in your web browser.
2. You might not see any obvious errors, but check your browser's console for runtime errors.
3. Open `bugSolution.html` to see the corrected code in action.