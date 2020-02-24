# HTML
### CH.7 Forms
**How Forms Work**
A user fills in a form and then presses a button to submit the information to the server.

**Form Structure**
Form controls live inside a `<form>` element.
Every `<form>` element requires an action attribute.
Forms can be sent using one of two methods: get or post.

**Text Input**
The `<input>` element is used to create several different form controls.
When the type attribute has a value of text, it creates a singleline text input.

**Password Input**
When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out.
The name attribute indicates the name of the password input.

**Text Area**
The `<textarea>` element is used to create a mutli-line text input.

**Radio Button**
`type="radio"`
Radio buttons allow users to pick just one of a number of options.
and has three attribute:
1. name.
2. value.
3. checked.

**Checkbox**
`type="checkbox"`
Checkboxes allow users to select (and unselect) one or more options in answer to a question.and has three attribute:
1. name.
2. value.
3. checked.

**Drop Down List Box**
The `<select>` element is used to create a drop down list box. It contains two or more `<option>` elements.it has a name attribute.

The `<option>` element is used to specify the options that the user can select from. and has a value & selected attributes.

**Multiple Select Box**
You can turn a drop down select box into a box that shows more than one option by adding the "size" attribute.
the "multiple" attribute with a value of multiple allows to select multiple options.

**File Input Box**
type="file"
This type of input creates a box that looks like a text input followed by a browse button. When the user clicks on the browse button, a window opens up that allows them to select a file from their computer to be uploaded to the website.

**Submit Button**
type="submit"
The submit button is used to send a form to the server.
- "name"
It can use a name attribute but it does not need to have one.
- "value"
The value attribute is used to control the text that appears on a button.

**Image Button**
type="image"
give the type attribute a value of image. The src, width, height, and alt attributes work just like they do when used with the `<img>` element.

**Button & hidden Controls**
The <button> element was introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button.

**Grouping Form Elements**
You can group related form controls together inside the `<fieldset>` element. This is particularly helpful for longer forms.


# CSS
### CH.14 Lists , Tables & Forms
**Bullet Point Styles**
The list-style-type property allows you to control the shape or style of a bullet point.
- Unordered Lists:
 - none.
 - disc.
 - circle.
 - square.
- Ordered Lists:
 - decimal.
 - decimal-leading-zero.
 - lower-alpha.
 - upper-alpha.
 - lower-roman.
 - upper-roman.

 **Images for Bullets**
 You can specify an image to act as a bullet point using the list-style-image property.

 **Positioning The Marker**
 list-styleposition property indicates whether the marker should appear on the inside or the outside of the box containing the main points. This property can take one of two values:
 1. inside.
 2. outside.

 **List Shorthand**
 list-style it allows you to express the markers' style, image and
position properties in any order.

**Gaps Between Cells**
border-spacing, border-collapse.


# JavaScrip
### CH.6 Events
**THE EVENT OBJECT**
When an event occurs, the event object tells you information about the event, and the element it happened upon.

**EVENT DELEGATION**
Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element.

**CHANGING DEFAULT BEHAVIOR**
The event object has methods that change:
the default behavior of an element and how the element's ancestors respond to the event.

**USER INTERFACE EVENTS**
User interface CUI) events occur as a result of interaction with the browser window rather than the HTML page contained within it, e.g., a page having loaded or the browser window being resized.

**FOCUS & BLUR EVENTS**
The HTML elements you can interact with, such as links and form elements, can gain focus. These events fire when they gain or lose focus.

**MOUSE EVENTS**
The mouse events are fired when the mouse is moved and also when its buttons are clicked.

**KEYBOARD EVENTS**
The keyboard events are fired when a user interacts with the keyboard
(they fire on any kind of device with a keyboard).

**MUTATION EVENTS & OBSERVERS**
Whenever elements are added to or removed from the DOM, its structure changes. This change triggers a mutation event.

**HTMLS EVENTS**
Here are three page-level events that have been included in versions of the HTMLS spec that have become popular very quickly.