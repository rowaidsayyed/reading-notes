# Welcome 201d3

Persistent local storage is one of the areas where native client applications have held an advantage over web applications
These values may be stored in the registry:
* INI files
* XML files

## potentially dealbreaking downsides for cookies:
* Cookies are included with every HTTP request, thereby slowing down the web application by needlessly transmitting the same data over and over
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless the entire web application is served over SSL)
* Cookies are limited to about 4 KB of data 

## userData 
* userData allows web pages to store up to 64 KB of data per domain

## HTML5 Storage
Certain browser vendors refer to it as “Local Storage” or “DOM Storage.”

### What is HTML5 Storage? 
it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies.

From JavaScript code, we can access HTML5 Storage through the localStorage object on the global window object.
But Before use it we should detect whether the browser supports it or not .using javascript code 

## USE HTML5 STORAGE
HTML5 Storage is based on named key/value pairs. we store data based on a named key, then we can retrieve that data with the same key.
* The named key is a **string**.
* The data can be **any type** supported by JavaScript.
* The data is actually stored as a *string*.
* If we store and retrieve anything other than strings, we need to use functions like `parseInt()` or `parseFloat()`.

## setItem and getItem
* we use getItem to get stored data
* we use setitem to store data
Calling `setItem()` with a named key that already exists will silently **overwrite** the previous value. Calling `getItem()` with a non-existent key will return **null** rather than throw an exception.

### Example
`var foo = localStorage.getItem("bar");`
// ...
`localStorage.setItem("bar", foo);`

Could be rewritten to use square bracket syntax instead:

`var foo = localStorage["bar"];`
// ...
`localStorage["bar"] = foo;`

## TRACKING CHANGES TO THE HTML5 STORAGE AREA
* If we want to keep track programmatically of when the storage area changes, we can trap the storage event.
* The storage event is fired on the window object whenever `setItem()`, `removeItem()`, or `clear()` is called 

## STORAGEEVENT OBJECT properties
1. key
2. oldValue
3. newValue
4. url or uri

