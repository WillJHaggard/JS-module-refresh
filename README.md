# Organizing JavaScript Functionality

In this exercise, you will modify and extend existing code to wire up some basic interactivity for a simple "cool site". The objective of this challenge is to exercise skills with basic JavaScript, including events and DOM interactions (using jQuery), as well as using basic best practices for organizing your code.

We will break this exercise into four tasks.

**Note:** The Ajax calls in this exercise will only work over `file://...` protocol if you're in Firefox. If you're using Chrome or IE, you'll need to run a local fileserver (like python's `SimpleHTTPServer`, Apache, IIS, etc) in the coding challenge directory, and load it into the browser using `http://localhost...` instead.

## Task 1

1. Open "header.js". In this file, you will attach event handlers for the header links. Use a jQuery "document-ready" event handler.



2. Refactor "header.js", "carousel.js", and "details.js" to use the "module pattern". Each file should expose one module name (`Header`, `Carousel`, and `Details`, respectively).
3. Each module's API should have at a minimum one method called `init()`, which you should wire up to be called by the jQuery "document ready" event.




4. Add a close button to the modal that works.
5. Add behavior so the "register" and "login" buttons also close the modal.


