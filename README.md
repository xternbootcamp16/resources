# TechPoint Xtern Bootcamp Resources

This is your day-by-day guide to what we've covered in class: the topics, the presentations, the code, the homework, and relevant links.

> If you're stuck, or if you want to learn all the gory details of a particular topic, start with [MDN (Mozilla Developer Network)](https://developer.mozilla.org/en-US/docs/Web/JavaScript), which is effectively the official documentation for JavaScript.

# Week 1

## Tuesday, May 31, 2016: Intro

### Topics
* History of JavaScript and the Web
* Getting the most out of a coding bootcamp
* Anatomy of an HTML element (tags, attributes, contents)
* Basic CSS selector syntax
  * Element name (`div`, `h1`, `p`, etc.)
  * Element ID (`#theID`, `div#theID`, etc.)
  * Class name (`.theClass`, `p.theClass`, etc.)
* Basic DOM manipulation
  * `document.querySelector`/`document.querySelectorAll`
  * `.innerText`/`.innerHTML`
* Basic event handling
  * `onsubmit`
  * Anonymous functions
  * `.preventDefault`

### Presentations
* [JavaScript History](https://www.dropbox.com/s/h5uq5rxtty7blm4/01%20JavaScript%20-%20History.key?dl=0) - Keynote (169 MB)
* [Bootcamp Tips](https://www.dropbox.com/sh/bcqn1bm2ubl044a/AAB6bTUOIMJv9uFrHfJ3dMp9a?dl=0) - Keynote (19.3 MB)

### Projects
* Basic Form (FirstJS):  [morning](https://github.com/xternbootcamp16/firstjs) | [afternoon](https://github.com/xternbootcamp16/firstjs-afternoon)

### Links

* [Foundation](http://foundation.zurb.com/) - a front-end framework
* [CSS Diner](http://flukeout.github.io/) - a game for practicing CSS selector syntax
* [CSS Selector Game](http://toolness.github.io/css-selector-game/) - another tool for practicing selector syntax

### Homework: Basic Form (FirstJS)

Grab values from form fields and add them to a list.

You'll need to employ these concepts that we used in class:
* Target elements with `document.querySelector`
* Handle events
* Prevent default event behavior from executing
* Alter an element's contents via `innerHTML`

### Baseline Goal:
* Display values as plain text.

**Bonus Credit**
* Display values in separate paragraphs.

**Mega Bonus Credit**
* Display values in an unordered list.

**Super Mega Bonus Credit**
* Display values in a _definition list_ (`<dl>`).

Output something like this:

```html
<dl>
  <li>
    <dt>First Name</dt>
    <dd>Davey</dd>
  </li>

  <li>
    <dt>Hair color</dt>
    <dd>#000000</dd>
  </li>

  <!-- etc. -->
</dl>
```

**Super Mega Bonus Credit Hyper Fighting**

Display the color value _in the specified color_.

> **Update**: [Solution](http://xternbootcamp16.github.io/firstjs-afternoon/)

## Wednesday, June 1, 2016: Objects and Functions

### Topics

* Functions
  * Function expressions
  * Functions as variables
  * Functions as object properties (_methods_)
  * Variable scope
  * IIFEs: Immediately Invoked Function Expressions
  * Function invocation and the value of `this`
    * As functions, _e.g._ `someFunction()`: `this === window` (_i.e._ the global object)
      * **Warning**: This includes functions defined within other functions.
    * As methods, _e.g._ `someObject.someMethod()`: `this === someObject` (_i.e._ the object on which the method was called)
    * As event handlers, _e.g._ `someForm.onsubmit = someFunction`: `this === someForm` (_i.e._ the object that fired the event)

* Objects
  * Object literals
  * Property naming
  * Retrieving property values
  * Setting property values

* DOM
  * Creating elements (`document.createElement('li')`)
  * Setting style properties on elements (`someElement.style.backgroundColor = 'CadetBlue'`)
  * Appending child elements (`someList.appendChild(someItem)`)

* Selectors
  * Descendent (`ul li`) and child (`ul > li`)

* CSS Properties
  * `background-color`
  * `border`
  * `height`
  * `list-style`
  * `width`

* Organizing Code
  * `.js` files (`<script src="app.js"></script>`)
  * Wrapping in an IIFE (`(function() {})();`)
  * Wrapping in a object-literal (`{}`)

### Presentations
* [Day 1 review, Day 2 intro](https://www.dropbox.com/s/uopok7a2pion0n9/02%20Functions.key?dl=0)

### Projects
* Finished Basic Form (FirstJS): [morning](https://github.com/xternbootcamp16/firstjs) | [afternoon](https://github.com/xternbootcamp16/firstjs-afternoon)

### Links

* [List of CSS color names](http://www.w3schools.com/colors/colors_names.asp)
* [IIFEs as explained by Ben Alman](http://benalman.com/news/2010/11/immediately-invoked-function-expression/), who coined the term
* [More than you ever wanted to know about _objects_](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)

### Homework: Megaroster

Create a class roster.

**Baseline Goal**
* User can enter a name to be added to the roster.
* Name will be added to the end of a list

**Bonus Credit**
* Create _at most_ one global variable.

**Mega Bonus Credit**
* Add names to the _top_ of the list.

**Super Mega Bonus Credit**
* Add a _delete_ link to every list item that removes the name from the list when clicked.

**Super Mega Bonus Credit Hyper Fighting**
* Add a _promote_ link to every list item that draws a border around that item when clicked.
