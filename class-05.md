# HTML

### CH.5 Images
**adding images**
To add an image into the page you need to use an `<img>` element. 
- _src:_ This tells the browser where it can find the image file.
- _alt:_ This provides a text description of the image which describes the image if you cannot see it.
- _title:_ You can also use the title attribute with the `<img>` element to provide additional information about the image.

**Height & Width of Images**
- height: This specifies the height of the image in pixels.
- width: This specifies the width of the image in pixels.

**Where to Place Images in Your Code**
1. before a paragraph.
2. inside the start of a paragraph.
3. in the middle of a paragraph.

**Old Code: Aligning Images Horizontally**
`align` The align attribute can take these horizontal values:
- left. 
- right.

**Old Code: Aligning Images Vertically**
`align` The align attribute can take these vertical values:
- top. 
- middle.
- bottom.

**Three Rules for Creating Images**
1. Save images in the right format.
2. Save images at the right size.
3. Use the correct resolution.

**image formates**
1. JPEG: Whenever you have many different colors in a picture you should use it.
2. GIF: Use GIF or PNG format when saving images with few colors or large areas of the same color.


# CSS

### CH.11 Colors
**forground color**
You can specify any color in CSS in one of three ways:
1. RGB values: example: rgb(100,100,90).
2. HEX code: For example: #ee3e80.
3. color names.

**contrast** 
When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

**CSS3: Opacity opacity, rgba**
it allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an **_alpha_** value and is a number between 0.0 and 1.0.

**CSS3: HSL Colors**
The value of the property starts with the letters hsl, followed by individual values inside parentheses.


### CH.12 Text
**Specifying Typefaces**
The font-family property allows you to specify the typeface that should be used for any text inside the element.

**Size of Type**
The font-size property enables you to specify a size for the font.
most common ways:
1. pixels.
2. percentages.
3. ems.

**More Font Choice**
@font-face allows you to use a font, even if it is not installed on the computer of the person browsing.

**Bold**
The font-weight property.There are two values that this property:
1. normal.
2. bold.

**Italic**
font-style property. There are three values this property can take:
1. normal.
2. italic.
3. oblique.

**UpperCase & LowerCase**
The text-transform property is used to change the case of text giving it one of the following values:
1. uppercase.
2. lowercase.
3. capitalize

**Underline & Strike**
The text-decoration property allows you to specify the following values:
1. none.
2. underline.
3. overline.
4. line through.
5. blink.

**Leading**
In CSS, the line-height property sets the height of an entire line of text, so the difference between the font-size and the line-height is equivalent to the leading.

**Letter & Word Spacing**
You can control the space between each letter with the letter-spacing property.

**Alignment**
The text-align property can take one of four values:
- left.
- right.
- center.
- justify.

**Vertical Alignment**
The vertical-align property It is not intended to allow you to vertically align text in the middle of block level elements such as `<p>` and `<div>`, although it does have this effect when used with table cells.
The values it can take are:
1. baseline
2. sub
3. super
4. top
5. text-top
6. middle
7. bottom
8. text-bottom

**Indenting Text**
The text-indent property allows you to indent the first line of text within an element.

**CSS3: Drop Shadow**
The text-shadow property It is used to create a drop shadow.

**First Letter or Line**
You can specify different values for the first letter or first line of text inside an element using:
`:first-letter` and `:first-line`.They are known as pseudo-elements.

**Styling Links**
there are two pseudo-classes that allow you to set different styles for links that have and have not yet been visited:
- :link.
- :visited.

**Responding to Users**
There are three pseudo-classes that allow you to change the appearance of elements when a user is interacting with them:
- :hover.
- :active.
- :focus.