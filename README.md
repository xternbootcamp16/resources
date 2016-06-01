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
* FirstJS:  [morning](https://github.com/xternbootcamp16/firstjs) | [afternoon](https://github.com/xternbootcamp16/firstjs-afternoon)

### Links

* [Foundation](http://foundation.zurb.com/) - a front-end framework
* [CSS Diner](http://flukeout.github.io/) - a game for practicing CSS selector syntax
* [CSS Selector Game](http://toolness.github.io/css-selector-game/) - another tool for practicing selector syntax

## Wednesday, June 1, 2016: Objects and Functions

### Topics

* Functions
  * Function expressions
  * Functions as variables
  * Functions as object properties (_methods_)
  * Variable scope
  * Function invocation
    * As functions (`this` is `window`)
    * As methods (`this` is the object)
    * As event handlers (`this` is the object on which the event fired)
  * IIFEs: Immediately Invoked Function Expressions

* Objects
  * Object literals
  * Property naming
  * Retrieving property values
  * Setting property values

* DOM
  * Creating elements
  * Setting style properties on elements
  * Appending child elements

* Organizing Code
  * `.js` files (`<script src="app.js"></script>`)
  * Wrapping in an IIFE
  * Wrapping in a object-literal

### Projects
  * Finished FirstJS: [morning](https://github.com/xternbootcamp16/firstjs) | [afternoon](https://github.com/xternbootcamp16/firstjs-afternoon)

### Homework: Megaroster

Create a class roster.

**Baseline goal**
* User can enter a name to be added to the roster.
* Name will be added to the end of a list

**Bonus Credit**
* Create _at most_ one global variable.

**Mega Bonus Credit**
* Add names to the _top_ of the list.

**Super Mega Bonus Credit**
* Add a _delete_ link to every list item that removes the name from the list when clicked.

** Super Mega Bonus Credit Hyper Fighting
* Add a _promote_ link to every list item that draws a border around that item when clicked.
