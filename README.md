# Uncommon HTML Error: Incorrect Element Selection in JavaScript

This repository demonstrates a subtle but common error in JavaScript when interacting with HTML elements, specifically when using `document.getElementById()`. The bug lies in the lack of quotes around the ID passed to `getElementById()`, resulting in unexpected behavior.

## Bug Description:
The provided HTML code attempts to modify the content of a div element with the ID "myDiv". However, the JavaScript code contains a syntax error in its `document.getElementById()` call. The correct way is to pass the ID as a string. The bug is shown in `bug.html` file.  The correct solution is in `bugSolution.html`.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser. You should see an error in the browser's developer console.
3. Then open `bugSolution.html`, which demonstrate the correct use of getElementById. 

## Bug Solution
The solution involves simply adding double quotes around the ID string in the `document.getElementById()` method call, ensuring it is passed as a string literal, which is the correct usage.