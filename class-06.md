# JavaScript

### CH.3 Functions, Methodes and Objects
#### Object Literals
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

- IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES.
- IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS.

**literal notation**
literal notation is the easiest way to creat objects.

**accessing an object and dot notation**
you can access properities or methodes of an object by using dot notation.
you can also access properities by square brackets.

### CH.5 Document Object Model
**THE DOM TREE IS A MODEL OF A WEB PAGE**
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.
Each node is an object with methods and properties.
Scripts access and update this DOM tree (not the source HTML file).
Any changes made to the DOM tree are reflected in the browser.

**changing DOM square**
methods that find elements in the DOM tree are called DOM queries. 

**accessing elements**
DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.

**methods that select indiviual elements**
`getElementById()` and `querySelector()` can both search an entire document and return individual elements. bothe use a similar syntax.

**NODELISTS: DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT**
When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element).

**selecting an element from a nodelist**
two ways to do it:
1. `the item()`
2. `array syntax`
both require the index number of the element you want.

**SELECTING ELEMENTS USING CLASS ATTRIBUTES**
The get El ementsByCl ass Name() method allows you to select elements whose c 1 ass attribute contains a specific value.

**SELECTING ELEMENTS BY TAG NAME**
The get El ementsByTagName () method allows you to select elements using their tag name.

**SELECTING ELEMENTS USING CSS SELECTORS**
querySe 1 ector() returns the first element node that matches the CSS-style selector. querySe 1ectorA11 () returns a Nodelist of all of the matches.

**repeating actions for an entire nodelist**
when you have a nodelist, you can loop through each node in the collection and apply the same statements to each.

**ACCESS & UPDATE TEXT WITH TEXTCONTENT (& INN ERTEXT)**
The textCon tent property allows you to collect or update just the text that is in the containing element (and its children).

**ACCESSING TEXT ONLY**
In order to demonstrate the difference between textContent and i nnerText, this example features a CSS rule to hide the contents of the <em> element.

**adding or removing html content**
1. the innerHTML
2. DOM mainpulation.

**ADDING AN ELEMENT TO THE DOM TREE**
createElement() creates an element that can be added to the DOM tree, in this case an empty `<li>` element for the list.

**REMOVING ELEMENTS VIA DOM MANIPULATION**
DOM manipulation can be used to remove elements from the DOM tree.

**REMOVING AN ELEMENT FROM THE DOM TREE**
This example uses the removeCh i 1 d () method to remove the fourth item from the list (along with its contents).

### Understanding The Problem Domain Is The Hardest Part Of Programming
**What is the hardest thing about writing code?**
- Learning a new technology.
- Naming things.
- Testing your code.
- Debugging.
- Fixing bugs.
- Making software maintainable.

**A familiar problem**
by taking away the problem domain, or making it so trivial that it is easily understood.


**Why problem domains are hard**
We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.

The big issue is that many problem domains are like a puzzle with a blurry picture or no picture at all.

As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

**What can you do about it?**
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1. Make the problem domain easier.
2. Get better at understanding the problem domain.

