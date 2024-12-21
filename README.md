# Uncommon HTML Bug: Incorrect use of textContent
This repository demonstrates an uncommon bug in HTML related to the use of the `textContent` property.  The `textContent` property is used to set or get the text content of a node, but it does not render HTML tags correctly.  This example shows how using `innerHTML` is crucial when including HTML within the text content.

## Bug Description
The initial `bug.html` file attempts to modify the text content of a div element using `textContent`.  This approach fails to render HTML tags correctly. The `bugSolution.html` shows the correct usage using `innerHTML`.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser. Observe that the changes made using `textContent` are rendered as plain text.
3. Open `bugSolution.html` in a web browser. Notice that changes made using `innerHTML` correctly render HTML tags.