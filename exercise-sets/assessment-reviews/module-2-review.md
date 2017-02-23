# Module 2 Review Questions and Exercises

## HTML

### Questions

1. What is the difference between an ID and a class?
2. What does it mean to write "semantic" HTML?

### Exercises

1. Write an HTML image tag to show an image called `profile-picture.jpg`.
2. Write a link tag that links to http://google.com.
3. Write the appropriate tag to link an HTML file to a script file called `main.js`.
4. Write an complete standard HTML document outline (including a DOCTYPE, and `<html>`, `<head>`, and `<body>` tags).

## CSS

### Questions

1. What is the box model?
2. What is the difference between block and inline elements?
3. What is responsive design?
4. Which selector is more specific, a tag selector or class selector?
5. Which text would be red in the following example?

  ```html
  <style>
    section p:last-child {
      color: red;
    }
  </style>

  <section>
    <p>First paragraph</p>
    <p>Second paragraph</p>
    <p>Third paragraph</p>
  </section>
  <section>
    <p>First paragraph</p>
    <p>Second paragraph</p>
    <p>Third paragraph</p>
  </section>
  ```

### Exercises

1. Write a CSS rule to turn the background color of the link with the `.btn` class blue on hover:

  ```html
  <a href="#" class="btn">Learn more</a>
  ```

2. Write a CSS rule to give the `.container` a maximum width of `980px` when the browser window is wider than `1200px`:

  ```html
  <div class="container">
    <h1>I'm a heading!</h1>
  </div>
  ```

## JavaScript

### Questions

1. What is the difference between global and local scope variables?
2. What is the difference between `==` and `===`?
3. What would the following log to the console?

  ```javascript
  console.log(5 === "5");
  ```

4. What is a callback?
5. What is an object?
6. What is a function?

### Exercises

1. Write a function `findLongestWord()` that takes an array of words and returns the length of the longest one.
2. Define a function `sum()` that sums all the numbers in an array of numbers. For example, `sum([1,2,3,4])` should return 10.
3. Write a function that takes a character (i.e. a string of length 1) and returns true if it is a vowel, false otherwise.

## DOM Scripting

### Questions

1. What does DOM stand for and what is it?

### Exercises

1. Write a JavaScript statement that finds the element with the ID, `next`, and saves it to a variable called `nextButton`:

  ```html
  <a href="#" id="next" class="btn">Next</a>
  ```

2. Write another line that updates the text of `nextButton` to `"Next image"`.
3. Write another line that adds a click event listener to `nextButton` so that when it's clicked the browser alerts `"Next image coming up."`.

## jQuery

### Questions

1. What is a JavaScript library and why do we use them?
2. What is jQuery for?

### Exercises

1. Write a statement to select all elements with the `.btn` class using a jQuery selector and save them to a variable called `buttons`:

  ```html
  <a href="#" id="next" class="btn">Next</a>
  <a href="#" id="beginning" class="btn">Beginning</a>
  <a href="#" id="previous" class="btn">Previous</a>
  ```

2. Write another line that adds a click event to the buttons that logs `'click'` to the console when the button is clicked. Use the jQuery syntax.

## Angular

### Questions

1. What is a controller?
2. What is a view?
3. What is a single page application?

## Git

### Questions

1. What command creates a new local Git repository?
2. What command would create a new branch?
3. What command would merge a branch called `bug-fix` into the `master` branch?
