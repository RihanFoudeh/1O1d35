# JS Object Literals; The DOM Summary

## What is an object and how it works?** <br>
- it groups variables and functions to create something for the real world. 
- **Variables** become known as **properties**. 
- **Functions** become known as **Methods**. 
- **Literal notation**: most popular way to create objects.
- Use **"Dots notation"** to access object or properties. Also, you can use **"square brackets"** for properties. <br> 
......................................................................................................... <br>
## Document Object Model : <br>

- It specifies how the browser should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. <br>

## DOM TREE : <br>
- It is a model of the web page stored in the browser's memory. 
- It consists of four main types of nodes; **The Document Node, Element Nodes,  Attribute nodes, and text nodes.**
- Each node is an object with methods and properties. 
- You can access and update the DOM tree by locating the node that represents the element you want to work with, then use its text content, child element, and attributes. 
- There are two different approaches to adding and removing content from a DOM tree; **the innerHTML and DOM manipulation.** <br>

## Caching Dom Queries : <br>
- They are the methods that find elements in the DOM tree. 
- They may return one element or collection of nodes (NodeList). 
- **getElementById() and querySelector()** can both search an entire document and return individual elements.
- **getElementById()** allows you to select a single element node by specifying the value of its id attribute. <br>

## NodeList: <br>
- They are a collection of element nodes. 
- The nodes element in NodeList stored in the same order as in HTML pages.
- They have s properties and methods. [length, item].
- **Static NodeList:** when your script updates the page, the NodeList is not updated. 
- **Live NodeList:**  when your script updates the page, the NodeList update too/  they are faster than static NodeLists. 
- There are four diiferent DOM queries that return a NodeList : **getElementsByTagName('hl ' ) / getElementsByTagName('li ') / getElementsByClassName('hot') / querySe l ectorA 11 ( ' l i [ id] ' )**
- There are two ways to select an element from a NodeList; **item() and array syntax**. [ **Array** syntax is preferred more because it's faster] 
- You can loop each node in NodeList and apply the same statement to each. 
