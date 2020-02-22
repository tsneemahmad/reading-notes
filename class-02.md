# HTML

### CH.2 TEXT
**Superscript & Subscript**
- The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts.
- The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas.

**Line Breaks & Horizontal Rules**
- if you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />`.
- To create a break between themes you can add a horizontal rule between sections using the `<hr />` tag.

**Quotations**
- The `<blockquote>` element is used for longer quotes that take up an entire paragraph.
- The `<q>` element is used for shorter quotes that sit within a paragraph.

**Citations & Definitions**
- the `<cite>` element can be used to indicate where the citation is from.
- The `<dfn>` element is used to indicate the defining instance of a new term.

**Changes to Content**
- The `<ins>` element can be used to show content that has been inserted into a document, while
- the `<del>` element can show text that has been deleted from it.
- The `<s>` element indicates something that is no longer accurate or relevant (but that should not be deleted).

# CSS
### CH.10 Introducing CSS
**CSS selectors**
- _child selector_ Matches an element that is a direct child of another. `li>a {}`
- _Adjacent Sibling_ Matches an element that is the next sibling of another Selector. `h1+p {}`
- _General Sibling_ Matches an element that is a sibling of another Selector. `h1~p {}`

**How Css Rules Cascade**
- last rule.
- specifity. 
- important: You can add !important after any property value.

**Inheritance**
You can force a lot of properties to inherit values from their parent elements by using inherit for the value of the properties.


# JavaSCript
### CH.2 basic javascript instructions
**ARRAYS**
An array is a special type of variable. It doesn't just store one value; it stores a list of values.
ex. : var colors;
colors = ['white', 'black', ' custom '];

**EXPRESSIONS**
1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE.
2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE.

**OPERATORS**
they allow us to create a single value from one or more values.

### CH.4 Decisions & loops
**logical operators**
comparison operators usually return single values of true or false. logical operators allow you to compare the results of more than one comparison operator.
- && : logical and
- || : logical or
- ! : logical not

**comparison operators: evaluating conditions**
 you can evaluate a situation by comparing one value in the script to what you expect it might be. the result will be a boolean: true or false.
- == : is equal to
 it compares two values to see if they are the same.
- != : is not equal to
- it compares two values to see if they are not the same.
- === : strict equal to
- it compares two values to check that both the data and value are the same.
- !== : strict not equal to
- it compares two values to check  that both the data and value are not the same.

**If statement**
it evaluates a condition, if the condition evaluates to true, any statement in the subsequent code block will be excuted.

**If...else statement**
it checks a condition. if it resolves to true the first code block is excuted. if it resolves to false the second code block will be excuted.