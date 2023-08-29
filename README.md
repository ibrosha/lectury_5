# lectury_5

# WHAT IS THE DOM ?

- The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

# The dom tree structure

![](/Без%20названия.png)

# DOM

- According to the Document Object Model (DOM for short), every HTML tag is an object. 
Subtags are "children" of the parent element. The text that is inside the tag is also an
object.All these objects are available with JavaScript, we can use them to modify the page.

- JavaScript can modify all HTML elements on a page.
- JavaScript can change all HTML attributes on a page.
 - JavaScript can change all CSS styles on a page.
- JavaScript can remove existing HTML elements and attributes.
- JavaScript can add new HTML elements and attributes.
- JavaScript can respond to all existing HTML events on the page.
- JavaScript can fire new HTML events on a page

- Definition and Usage. The querySelector() method returns the first child element that matches a 
specified CSS selector(s) of an element, querySelectorAll() method can be used to access all elements 
which match with a specified CSS selector

# array methods

- innerHTML - Это свойство предоставляет простой способ полностью 
заменить содержимое элемента. Например, все содержимое 
элемента body может быть удалено:

- The Style object represents an 
individual style statement.


# Html events …

### An HTML event can be something the 

browser does, or something a user does.
Here are some examples of HTML events:
•An HTML web page has finished loading
•An HTML input field was changed
•An HTML button was clicked


### JavaScript lets you execute code when events are detected.


# createElement()

- The JavaScript document.createElement() method allows you to create and return a 
new element (an empty Element node) with the specified tag name.

1 - createElement(elementName): Creates an html element whose tag is
passed as a parameter. Returns the created element

# The createElement() Methods
# The createElement() method creates an element node.

# HTML DOM Element appendChild()

- The appendChild() method appends a node (element) as the last
child of an element.
appendChild() adds a node to the end of the list of children of the 
specified parent node. If the given child element is a reference to 
an existing node in the document, then the appendChild() 
function moves it from its current position to the new position

# To create a paragraph with a text.
•Create a paragraph element
•Create a text node
•Append the text node to the paragraph
•Append the paragraph to the document.


### // Create a p element:
const para = document.createElement("p");
// Create a text node:
const node = document.createTextNode("This is a paragraph.");
// Append text node to the p element:
para.appendChild(node);
// Append the p element to the body:
document.getElementById("myDIV").appendChild(para);

# classlist()

# ClassList is a getter. The object it returns has several methods:

- add( String [,String] ) 
Adds the specified classes to the element

- remove( String [,String] ) 
Removes the specified classes from the element

- toggle(String[, Boolean]) 
If the element has no class, it adds it, otherwise it removes it. When
false is passed as the second parameter, it removes the specified
class, and if true, it adds it.

- If the second parameter is undefined or a variable with
typeof == 'undefined', the behavior is the same as passing only the
first parameter when calling


