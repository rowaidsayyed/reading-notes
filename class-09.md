# Welcome 201d3

## Forms
There are several types of form controls that you can use to collect information from visitors to your site.
* ADDING TEXT:
* Making Choices:
* Submitting Forms:
* Uploading Files:

### How Forms Work
1. A user fills in a form and then presses a button to submit the information to the server.
2. The name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language .
4. The server creates a new page to send back to the browser based on the information received.

### Form Structure
Form controls live inside a `<form>` element.
This element should always carry the action attribute

* Forms can be sent using one of two methods: 
  * get
  * post

#### get
* short forms (such as search boxes)
* when you are just retrieving data from the web server


#### post
* allows users to upload a file
* is very long 
* contains sensitive data (e.g. passwords)
* adds information to, or deletes information from, a database

### Text Input
1. `<input>`
	* type="text"
    * type="password"
	* type="radio"
	* type="checkbox"
	* type="file"
	* type="submit"
	* type="image"
	* type="hidden"
2. `<textarea>`
3. `<select>`
4. `<button>`

**`<label>` each form control should have its own `<label>` element**

### field set
we can group related form controls together inside the `<fieldset>` element.
The `<legend>` element can come directly after the opening `<fieldset>` tag and contains a caption

### HTML5
* Form Validation
* Date Input
* Email & URL Input
* Search Input

## Lists
### Bullet Point styles
* list-style-type
* list-style-image
* list-style-position

## Table
* width
* padding
* text-transform
* font-size
* text-align
* background-color
* :hover



## Events

> When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.

### HOW EVENTS TRIGGER JAVASCRIPT CODE
1. SELECT ELEMENT
2. SPECiFY EVENT
3. CALL CODE

### WAYS TO BIND AN EVENT TO AN ELEMENT
1. HTML EVENT HANDLERS (DO NOT USE)
2. TRADITIONAL DOM EVENT HANDLERS
3. DOM LEVEL 2 EVENT LISTENERS

#### EVENT LISTENERS
Event listeners are a more recent approach to handling events.

#### Event Flow
HTML elements nest inside other elements
* flow of events only matters when the code has event handlers on an element and one of its ancestor or decendant element

#### THE EVENT OBJECT
When an event occurs, the event object tells
us information about the event
