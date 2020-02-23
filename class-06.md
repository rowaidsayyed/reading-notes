# Welcome 201d3

## The Problem Domain
Understanding The Problem Domain Is The Hardest Part Of Programming
What is the hardest thing about writing code?

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable
The real world is a messy place.  Many of the problem domains we face as programmers are difficult to understand and look completely different depending on our viewpoint.

As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

> Programming is easy if you understand the problem domain
so we can often make the problem domain easier by cutting out cases and narrowing our focus to a particular part of the problem.

## Object
> Object: a set of variables and functions to create a model of a something you would recognize from the real world.

In an object, variables=properties and functions=method

Literal notation
its a way to creat objects, object is the carly brackets and their contents we need a colon to separete each key from its value and we need comma to separate property and method

Note: we can access the properties or methods of an object using dot notation or we can access properties using square brackets

## Document object model(DOM)
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

Note: Any changes made to the DOM tree are reflected in the browser.

* Attribute nodes are not children of the element thar
carries them; they are part of that element.
* Text nodes cannot have children.

Accessing and updating the DOM tree:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes.


**Methods that find element in the DOM tree are called DOM queries**

## SELECTING AN ELEMENT FROM A NODELIST
1. item() method
2. array method

### To add HTML content we can use 
1. innerHTML property
2.  1. createElement ()
    2. createTextNode()
    3. appendChild()

### To remove HTML content we can use 
1. innerHTML property
2.  1. STORE THE ELEMENT TO BE REMOVED IN A VARIABLE
    2. STORE THE PARENT OF THAT ELEMENT IN A VARIABLE `parentNode`
    3. REMOVE THE ELEMENT FROM ITS CONTAINING ELEMENT `removeChild()`

### Cross-Site Scripting Attacks(XSS)
If we add HTML to a page using innerHTML (or several jQuery methods),we need to be aware of XSS; otherwise,
an attacker could gain access to our users' accounts.
