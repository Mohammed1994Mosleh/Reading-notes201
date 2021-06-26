# class 06 Reading:
## object:
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

## literal object:
literal notation is the easiest and most popular way to declare object.

## Accessing an object and dot notation:
you access the properites and method using dot notation,you can also access properites using squre brackets.

Document object model:
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
![DOM](https://miro.medium.com/max/952/1*wgCcUtfyvkoUXYBRBzEomA.png)

### WORKING WITH THE DOM TREE:
Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.

### ACCESSING ELEMENTS:
DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

- GROUPS OF ELEMENT NODES
If a method can return more than one node, it will
always return a Nodelist, which is a collection of
nodes (even if it only finds one matching element).
You then need to select the element you want from
this list using an index number (which means the
numbering starts at 0 like the items in an array).
- FASTEST ROUTE:
within your web page will make the page seem
faster and/or more responsive. This usually means
evaluating the minimum number of nodes on the
way to the element you want to work with.

- getElementByld( 1 id 1
)
Selects an individual element given the value of its i d attribute .
The HTML must have an id attribute in order for it to be selectable.
First supported: IE5.5, Opera 7, all versions of Chrome, Firefox, Safari.
- querySel ector( 1css selector ')
Uses CSS selector syntax that would select one or more element s .
This method returns only the first of the matching elements.
- getEl ement sByClassName( 1class 1
)
Selects one or more elements given the va lue of their cl ass attribute.
The HTML must have a cl ass attribu te for it to be selectable.
This method is faster than querySe 1ectorA11 () .
- getEl ementsByTagName( 1 tagName 1
)
Selects all elements on the page with the specified tag name.
This method is faster than querySe 1ectorA11 ().
- querySelectorAll ( 1css select or •)
Uses CSS selector syntax to select one or more elements and returns all
of those that match.

### SELECTING AN ELEMENT FROM A NODELIST:
1. THE tern{) METHOD:
Nodelists have a method
called item() which will return
an individual node from the
Node list.
2. Array syntax

### SELECTING ELEMENTS USING CLASS ATTRIBUTES:
The get El ementsByCl ass Name()
method allows you to select
elements whose c 1 ass attribute
contains a specific va lue.

### SELECTING ELEMENTS BY TAG NAME
The get El ementsByTagName ()
method allows you to select
elements using their tag name.
### SELECTING ELEMENTS USING CSS SELECTORS:
querySe 1 ector() returns
the first element node that
matches the CSS-style selector.
querySe 1ectorA11 () returns a
Nodelist of all of the matches.
### LOOPING THROUGH A NODELIST:
If you want to apply the same
code to numerous elements,
looping through a Nodelist is a
powerful technique.
### TRAVERSING THE DOM:
When you have an element node, you can select
another element in relation to it using these five
properties. This is known as traversing the DOM.
1. parentNode
This property finds the element
node for the containing (or
parent) element in the HTML.
(1) If you started with the
first <l i >element, then its
parent node would be the one
representing the <ul >element
2. previousSibling
nextSibling
These properties find the
previous or next sibling of a node
if there are siblings.
If you started with the first <1 i >
element, it would not have a
previous sibling. However, its next
sibling (2) would be the node
representing the second <l i >.
3. f i rstChil d
lastChild
These properties find the first or
last child of the current element.
If you started with the <u 1 >
element, the first child would be
the node representing the first
<l i> element, and (3) the last
child would be the last <1 i >.


## ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML
Using the i nnerHTML property, you can access
and amend the contents of an element,
including any child elements.

## CROSS-SITE SCRIPTING (XSS) ATTACKS:
If you add HTML to a page using i nnerHTML (or several jQuery methods),you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, an attacker could gain access to your users' accounts