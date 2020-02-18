# HTML

### Ch.4 Links
**writing links**
Links are created using the `<a>` element. Users can click on anything
between the opening `<a>` tag and the closing `</a>` tag. You specify
which page you want to link to using the href attribute.

**directory structure**
On larger websites it's a good idea to organize your code by placing the
pages for each different section of the site into a new folder.

**relative URLs**
they can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

**relative link types:**
_Same Folder:_ just use the file name.
_Child Folder:_ use the name of the child folder, followed by a forward slash, then the file name.
_Grandchild Folder:_ Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name.
_Parent Folder:_ Use ../ to indicate the folder above the current one,  
then follow it with the file name.
_GrandParent Folder:_ Repeat the ../ to indicate that you want to go up
two folders (rather than one), then follow it with the  file name.

**email links**
use the `<a>` element and inside it the attribute starts with mailto: and is followed by the email address you want the email to be sent to.

**opening links in  new window**
use the target attribute on the opening `<a>` tag. The value of this attribute should be _blank.

**linking to a specific part of a page**
To link to an element that uses an id attribute you use the `<a>`, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to.

# CSS

### CH.15 Layout
**Controll ing the Position of Elements**
CSS has the following positioning schemes that allow you to control the layout of a page:
1. _normal flow:_ In normal flow, each block-level element sits on top of the next one. the syntax would be: `position: static;`
2. _Relative Positioning:_ Relative positioning moves an element in relation to where it would have been in normal flow. indicate that using the position property with a value of relative.
3. _Absolute Positioning:_ the box is taken out of normal flow and no longer affects the position of other elements on the page. indicate that using the position property with a value of absolute.
  - _Fixed Positioning:_ is a type of absolute positioning that requires the position property to have a value of fixed. `position:fixed`.

**Overlapping Elements**
If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front.

**Floating Elements**
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

**Clearing Floats**
The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:
- left.
- right.
- both.
- none.

**Creating Multi-Column Layouts with Floats**
The following three CSS properties are used to position the columns next to each other:
- width.
- float.
- margin.

**Fixed width layout**
To create a fixed width layout, the width of the main boxes on a page will usually be specified in pixels (and sometimes their height, too).

**A Liquid Layout**
The liquid layout uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen.


# JavaScript

### CH.3 Functions, Methodes and Objects
**what is a function?**
Functions let you group a series of statements together to perform a
specific task.

**declaring a function**
to creat a function you give it a name and then write the statement needed to acheive its tasks inside the curly braces.

**calling a function**
you can execute all the statements between its curly braces by one line of code. by writing the function name followed by semi-colon.

**declaring functions that need information**
in such cases when you declare the function you give it a parametrs.
inside the function, the parametrs act like variables.

**calling functions that need information**
specify the value it should use in the parantheses that follow its name. the values are called _arguments_ and they cn be provided as values or variable.

**getting a single value out of a function**
some functions return information to the code that called them.

**getting multiple values out of a function**
functions can return more than one value using array.


### 6 Reasons for pair programming
**How it works?**
pair programming commonly involves two roles: the Driver and the Navigator.

**Why pair program?**
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness