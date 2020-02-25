# CSS

### CH.15 Layout
**Controlling the Position of Elements**
CSS has the following positioning schemes that allow you to control the layout of a page:
1. _normal flow:_ In normal flow, each block-level element sits on top of the next one. the syntax would be: `position: static;`
2. _Relative Positioning:_ Relative positioning moves an element in relation to where it would have been in normal flow. indicate that using the `position: relative;`.
3. _Absolute Positioning:_ the box is taken out of normal flow and no longer affects the position of other elements on the page. indicate that using the `position: absolute;`.
  - _Fixed Positioning:_ is a type of absolute positioning that requires the position property to have a value of fixed. `position: fixed;`.

**Overlapping Elements**
If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front.

**Floating Elements**
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

**Clearing Floats**
The clear property allows you to say that no element (within the same containing element) should touch the left or right hand sides of a box. It can take the following values:
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