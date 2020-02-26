# class-09

## Forms
best way to collect information from visitors.

Form elements are different types of input elements, like:*text fields, checkboxes, radio buttons, submit buttons,* and more.

The \<input> element is **the most important** form element.

**Examples:**
* \<input type="text">   	*Defines a single-line text input field.*
* \<input type="radio">	*Defines a radio button (for selecting one of many choices)*
* \<input type="submit">	*Defines a submit button (for submitting the form)*


**The \<label> tag** defines a label for many form elements.
The <label> element is for *screen-reader users*, the screen-reader will *read out load the label* when the user is focused on the input element.


## Lists (CSS)
The Css lists properties allows to do:

* Set different list item markers for ordered lists.*list-style-type: circle;*
* Set different list item markers for unordered lists.
 *list-style-type: upper-roman;*
* Set an image as the list item marker. *list-style-image: url('sqpurple.gif');*   
* Add background colors to lists and list items.


**Position The List Item Markers:**

The *list-style-position* property specifies the position of the list-item markers (bullet points).

"list-style-position: outside;" means that the bullet points will be outside the list item

"list-style-position: inside;" means that the bullet points will be inside the list item.

**Table Borders** 

         table, th, td { border: 1px solid black; }

The **border-collapse** property sets whether the table borders should be collapsed into a single border.

For border around the table, only specify the border property for \<table>

The **text-align** property sets the horizontal alignment *(like left, right, or center)*.

For **zebra-striped** tables, use the nth-child() selector and add a background-color to all even (or odd) table rows:
          
          tr:nth-child(even) {background-color:#f2f2f2;}


## Events:

HTML events are "things" that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can "react" on these events.  

**Events** are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them in some way if desired. 

**For example**; *if the user clicks a button on a webpage*, you might want to respond to that action by displaying an information box.

Some **examples** of **HTML** events:

* An HTML web page has finished loading.
* An HTML input field was changed.
* An HTML button was clicked.



