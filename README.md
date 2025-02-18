# Uncommon HTML Error: Accessing Non-Existent Properties

This repository demonstrates a common error encountered when working with the Document Object Model (DOM) in HTML and JavaScript. The error arises when attempting to access a property that does not exist on a DOM element. 

The `bug.html` file contains the erroneous code. The `bugSolution.html` file shows the corrected version. 

## Error Description

The error message is "Uncaught TypeError: Cannot read properties of undefined (reading 'textContent')". This occurs because the code tries to access the `textContent` property of a property (`nonExistentProperty`) that is not defined on the `myDiv` element.