# Uncommon HTML Bug: innerHTML on Non-Existent Element

This repository demonstrates an uncommon error that can occur when working with HTML and JavaScript's `innerHTML` property. The error occurs when trying to manipulate the `innerHTML` of an element that does not exist in the DOM.

## Bug Description

The bug arises from an attempt to use `document.getElementById()` to access an element that has not been defined in the HTML document. Attempting to modify `innerHTML` of a non-existent element will throw an error and stop script execution.

## Bug Solution

The solution involves adding a check to see if the element exists before attempting to manipulate it.  This prevents the error and ensures the script runs smoothly.

## How to reproduce
1. Clone this repository.
2. Open bug.html in your browser. 
3. Observe the error in your browser's console.
4. Open bugSolution.html to see the corrected code.