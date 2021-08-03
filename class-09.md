# sumarize
## The <form> Element
* The HTML `<form>` element is used to create an HTML form for user input:
* The HTML `<input>` element is the most used form element.An `<input>` element can be displayed in many ways, depending on the `type` attribute.
* The `<input type="radio">` defines a radio button.
Radio buttons let a user select ONE of a limited number of choices.

* he `<input type="checkbox">` defines a checkbox.Checkboxes let a user select ZERO or MORE options of a limited number of choices.
* **The `<input type="submit">` defines a button for submitting the form data to a `form-handler`.The `form-handler` is typically a file on the server with a script for processing input data.The form-handler is specified in the form's `action` attribute.**



## css forms

 ### you can use attribute selectors:
* input[type=text] - will only select text fields
* input[type=password] - will only select password fields
* input[type=number] - will only select number fields
etc..
#### some os style 
 * Use the width `property` to determine the width of the input field:

* Use the padding property to add space inside the text field.
* Use the `border` property to change the border size and color, and use the `border-radius` property to add rounded corners,If you only want a bottom border, use the border-bottom property:
* Use the `background-color` property to add a background color to the input, and the `color` property to change the text color
* Use the :`focus` selector to do something with the input field when it gets focus You can remove this behavior by adding `outline: none;` to the input.
* If you want an icon inside the input, use the `background-image `property and position it with the `background-position` property.
*  transition property to animate the width of the search input when it gets focus.
* `resize` property to prevent textareas from being resized (disable the "grabber" in the bottom right corner):
* The `Name` Attribute for `<input>` Notice that each input field must have a `name attribute` to be submitted.If the name attribute is omitted, **the value of the input field will not be sent at all.**

## JavaScript Events
HTML events are "things" that happen to HTML elements.When JavaScript is used in HTML pages, JavaScript can "react" on these events.

#### Here is a list of some common HTML events:

* onchange :	An HTML element has been changed
* onclick	:The user clicks an HTML element
* onmouseover	:The user moves the mouse over an HTML element
* onmouseout:	The user moves the mouse away from an HTML element
* onkeydown:	The user pushes a keyboard key
* onload:	The browser has finished loading the page




