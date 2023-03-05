# Javascript
JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc.

## JavaScript HTML DOM

1. [ DOM Introduction ](#introduction)
    - [ What is the DOM? ](#dom)
3. [ DOM JavaScript Method ](#method)
    - [ The DOM programming interface ](#interface)
5. [ DOM JavaScript Document ](#syntax)

<a name="introduction"></a>
- ## The HTML DOM (Document Object Model)

With the HTML DOM, JavaScript can access and change all the elements of an HTML document.

The HTML DOM (Document Object Model)

When a web page is loaded, the browser creates a Document Object Model of the page.

The HTML DOM model is constructed as a tree of Objects:

With the object model, JavaScript gets all the power it needs to create dynamic HTML:
- JavaScript can change all the HTML elements in the page
- JavaScript can change all the HTML attributes in the page
- JavaScript can change all the CSS styles in the page
- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page

<a name="dom"></a>
### What is the DOM?
The DOM is a W3C (World Wide Web Consortium) standard.

The DOM defines a standard for accessing documents:

"The W3C Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document."

The W3C DOM standard is separated into 3 different parts:

Core DOM - standard model for all document types
XML DOM - standard model for XML documents
HTML DOM - standard model for HTML documents

<a name="method"></a>
- ## JavaScript - HTML DOM Methods
HTML DOM methods are actions you can perform (on HTML Elements).

HTML DOM properties are values (of HTML Elements) that you can set or change.

<a name="interface"></a>
### The DOM programming interface
The HTML DOM can be accessed with JavaScript (and with other programming languages).

In the DOM, all HTML elements are defined as `objects`.

The programming interface is the properties and methods of each object:
- A `property` is a value that you can get or set (like changing the content of an HTML element).
- A `method` is an action you can do (like add or deleting an HTML element).

The following example changes the content (the innerHTML) of the <p> element with id="demo":
````
<html>
<body>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello World!";
</script>

</body>
</html>
````
⚠️ In the example above, 'getElementById' is a `method`, while 'innerHTML' is a `property`.


    
