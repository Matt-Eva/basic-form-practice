# basic-form-practice

In this basic practice challenge, we'll be using a form to update our DOM.

Fork and clone down this repo to get started. You'll be writing all of your code in the `index.js` file. It's already connected to your `index.html` file. You won't need to run `json-server` or make any fetch requests in this basic practice.

### Basic Form Practice

We currently have a form that allows users to create a new note for themselves. When a user submits a new note, we want their note to be displayed in a new `li` within the `ul` that has the id `note-list`.

### Practicing Parse-Int

We have another form that allows users to increase a value. We want to use the form to update
the value of the number displayed in our paragraph by adding the value entered into the form to the value that's currently displayed. We DO still want to display the text "New Value:" along with the new win-record number.

Note that the value of all form inputs are registered as
strings in JavaScript. To convert strings into integers, you have to pass the string to the `parseInt` method. `parseInt` receives a string representing an integer as its argument and outputs the integer itself as a number. You will need to use parseInt to complete
this portion of the challenge.

### parseInt with Buttons

Instead of a form, let's imagine we're building a like button into our page. Our likes start off at zero, but we want people to be able to add likes by clicking our like button.

We also want to decrease the number of likes by clicking our dislike button. But, we don't want our number of likes to go below zero! (Sounds like we have a <em>condition</em> we need to check for.)

That's all! There are no tests for this lab - you just need to make sure it's working correctly.
