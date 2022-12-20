# Learning Log

## 2022-12-13 The Journey Begins

### Hosting
- had previously purchased a web domain (cyrusolinger.com) but never used it
- figured out how to transfer it from namecheap to bluehost for better webhosting options

### Code Editor
- installed VS Code
- installed live server extension, feels easier/faster?

### Version Control
- learned about git and GitHub
- learned basic commands: clone, push, add, commit, status, log

### HTML
- learned some basic tags: paragraphs, headings, bold text, italicized text, comments, ordered and unordered lists, links, images

### cyrusolinger.com
- added an unordered list of random facts about me
- added an ordered list of basketball greats
- added an image (relative link) of Alex Honnold with an alt and caption
- added a link to another page within my directly (./pages/about.html)

### Notes
- figured out how to point nameservers with namecheap hosting for dreamhoops.com
- published the site successfully
- learned how to use FTP via FileZilla (concerned about security?)
- got stuck trying to use GitHub as a source for my personal site as opposed to the cPanel File Manager or FTP


## 2022-12-14

### Project
- created first project
- basic recipe website with link to a recipe

### CSS
- basic ways to select HTML items
- combinators and chaining of selectors
- IDs vs Classes
- font and color options
- height and width
- the cascade: what determines which rules actually get applied to our HTML
- external vs internal vs inline CSS
- box model
 - padding increases the space between the edge of a box and the content inside of it.
 - margin increases the space between a box and any others that sit next to it.
 - border adds space (even if it’s only a pixel or two) between the margin and the padding.
- box-sizing: border-box is the alternative but common choice among devs.
- divs and spans

### "Flow"
- block vs inline vs inline-block
 - block: elements will appear on the page stacked atop each other
 - inline: appear in line with whatever elements they are placed beside
 - inline-block: behave like inline elements, but with block-style padding and margin

### Inspector
- opening the Chrome inspector
- selecting page elements
- changing styles (temporarily) in real time

### Flexbox
- used for positoning
- flex container is defined by having "display: flex"
- flex item lives in the flex container
- nesting can occur and an element can be bother a container and an item
- "flex" declation is shorthand for three properties
 - flex-grow
 - flex-shrink
 - flex-basis
- axes
 - flex-direction: row/column
- alignment
 - justify-content aligns items across the main axis
 - align-items aligns items across the cross axis
- IMPORTANT: Because justify-content and align-items are based on the main and cross axis of your container, their behavior changes when you change the flex-direction of a flex-container.
- gap: new property that performs similar to margin

### landing-page Project
- took a lot longer than expected
- worked on the navbar for a good 90 minutes
- need to perfect my understanding of positioning using flexbox
- many questions about nesting divs (compartmentalization vs simplicity?)

- completed the MVP of the 'hero' section

### cyrusolinger.com
- didn't work on it today
- spent more time than expected on TOP landing-page project
- plan to practice building a navbar tomorrow

### Notes
- installed IMWheel via terminal, mainly copy and pasting but felt cool to solve the scroll wheel issue

## 2022-12-15 Starting JavaSCript!

### JavaScript
- variable = storage container
- basic math with operators
- name the eight data types in JavaScript.
- understand the difference between single, double, and backtick quotes.
- embed a variable/expression in a string.
- understand what a method is.
- name the three logical operators.
- understand what the comparison operators are.
- understand what conditionals are.
- understand what nesting is.
- understand what truthy and falsy values are.
- how to define and invoke different kinds of functions.
- how to use the return value.
- what function scope is.

### JS Dev Tools
- change screen size of a website with developer tools
- view and change the DOM
- debug JavaScript
- use breakpoints
- view and edit HTML in the Elements tab
- view the Resources Panel to check the scripts running on a website
- add CSS Pseudostate to a Class
- view CSS Properties in Alphabetical Order
- view and edit the Box Model of any Element in Chrome DevTools
- view a page in print mode
- enable or Disable CSS Classes
- simulate media queries in Device Mode

### cyrusolinger.com
- completed basic navbar
 - took less than 10 minutes compared to 90 minutes on TOP landing-page
- created "Projects" section
 - practiced more flexbox
 - tried to improve css readability
 - improved efficiency of div usage
- added "container" div around everything
 - flex direction column
 - commented this out later
- gained some inspiration from other portfolio sites

- really like https://www.rshah.org/

## 2022-12-16

### Problem-Solving
- understanding the problem
 - write it in plain English
  - psuedocode
 - map it out (diagram)
 - what are the possible inputs and desired outputs?
- break large problem down into small problems

### Errors
- Syntax Error: occurs when the code you are trying to run is not written correctly, in accordance with the grammatical rules of JavaScript
- ReferenceError: whatever variable you are trying to reference does not exist (within the current scope)
- TypeError: 
 - an operand or argument passed to a function is incompatible with the type expected by that operator or function;
 - or when attempting to modify a value that cannot be changed;
 - or when attempting to use a value in an inappropriate way.

 ### Rock Paper Scissors Project
- struggled with passing in functions
  - wasn't sure when to use parentheses outside of defining the function
- compeleted MVP with minimal outside resources
- breakpoints in debugger were helpful, want to improve on using it
- tried to build the app all at once as opposed to breaking it down

## 2022-12-18

### Notes
- took the weekend off for the most part, practicing balance...

## 2022-12-19

### JS Exercises
- spent all day working on TOP JS exercises
- was able to complete the first 9 without checking solutions
- fibonacci sequence exercise could not solve one edge case
- moving on to DOM lecture and will return to these exercises later on

### DOM Manipulation
- skimmed through basics of DOM manipulation
 - selecting elements
 - creating elements
 - changing elements attributs
  - changing styles
  - adding/removing classes
 - attaching/removing nodes
 - looping nodes

 ### Notes
 - will work on Wes Bos JS30 project tomorrow for DOM practice
 - should have more skills to practice on personal site