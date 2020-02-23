# Domain Modeling

the process of creating a conceptual model in code for a specific problem.
A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain.

**Define a constructor and initialize properties**
To define the same properties between many objects, you'll want to use a constructor function.

**Generate random numbers**
To model the random nature of user behavior, you'll need the help of a random number generator. Fortunately, the JavaScript standard library includes a Math.random() function for just this sort of occasion.

# HTML
### CH>6 Tables
**Basic Table Structure**
The `<table>` element is used to create a table. The contents of the table are written out row by row.

You indicate the start of each row using the opening `<tr>` tag.
Each cell of a table is represented using a `<td>` element.

**Table Headings**
The `<th>` element its purpose is to represent the heading for either a column or a row.

**Spanning ColumnS**
The colspan attribute can be used on a `<th>` or `<td>` element and indicates how many columns that cell should run across.

**Long Tables**
- The headings of the table should sit inside the `<thead>` element.
- The body should sit inside the `<tbody>` element.
- The footer belongs inside the `<tfoot>` element.


# JavaScript
### CH.3 Functions, Method and Objects
**THE BROWSER OBJECT MODEL**
THE WINDOW OBJECT: The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser.

**THE DOCUMENT OBJECT MODEL**
The topmost object in the Document Object Model (or DOM) is the document object. It represents the web page loaded into the current browser window or tab.

**GLOBAL OBJECTS**
- STRING OBJECT: Whenever you have a value that is a string, you can use the properties and methods of the String object on that value.
- NUMBER OBJECT: Whenever you have a value that is a number, you can use the methods and properties of the Number object on it.
- MATH OBJECT: The Math object has properties and methods for mathematical constants and functions.
- DATE OBJECT (AND TIME): Once you have created a Date object, the following methods let you set and retrieve the time and date that it represents:
  - getDate().
  - getDay ().
  - getFull Year().
  - getHours().
  - getMinutes().
