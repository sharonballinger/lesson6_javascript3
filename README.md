## Project Name:  Photo Gallery Application

### Course Title:
Web Application Development

### Assignment Date:  
July 31, 2017

### Student Name:  
Sharon Ballinger

### Project Description:
Creating dynamic HTML using the Document Object Model.

### View Project:
https://sharonballinger.github.io/lesson6_javascript3/

### Lessons Learned in the Assignment:

#### **1. What is the DOM?**
The **DOM** stands for **Document Object Model**. The DOM describes the relationship between different elements, tags, attributes and text that make up a HTML page. By adding and/or deleting these elements of the HTML page the DOM structure changes *(see Manipulating the DOM)*. The DOM isn't the HTML code you write but it is the structure of your HTML code when loaded in a browser. Javascript is used to change, add, remove HTML elements and attributes, when the DOM is altered the web page is automatically updated. This is a way to add interactivity to the web page and for the client to have a custom experience.


#### **2. The DOM tree.** 
There's a big apple tree growing in the garden. There is the ground (root) then a big solid trunk growing out of the ground (element), from the trunk there's two branches (child), one of these branches has three branches (attribute) these branches can only contain three types of branches: element, text and comment. The text branch is the only branch that can flower an apple (child). When accesing the parts of the tree to change the status they are referred to as **nodes**: a root node, element nodes, attribute nodes and child nodes.

##### DOM hierarchy
```
> DOCUTYPE (Document)
>    |
>    |- ROOT (HTML)
>        |
>        |- ELEMENT (Head) "I am the child of ROOT"
>        |    |
>        |    |- ELEMENT (Title) "I am not a child node"
>        |         | 
>        |         |- TEXT ("Text") "I am a child node"
>        |
>        |- ELEMENT (Body) "I am the child of ROOT"
>             |
>             |- ELEMENT (h1) "I am the parent of text"
>             |    | 
>             |    |- TEXT ("Text")
>             | 
>             |- ELEMENT (a) 
>                  |    |
>                  |    |- ATTRIBUTE ("href")
>                  |
>                  |- TEXT ("Text")


```

#### **3. Manipulating the DOM.**
There are different computer programming languages that enable the manipulation of the DOM; JavaScript is one of these. With JavaScript we can change HTML elements and attributes, CSS styles, react to events, and create new events. By understanding the tree hierarchy and the relationship of the nodes the DOM can be   manipulated. The different tree nodes that can be manipulated are: `parentNode, childNodes, firstChild, nodeValue` or `nextElementSibling`. 

By referencing elements within the HTML such as `body` or `span` and using a method of the `document` object:  `document.getElementsByTagName('body')[0].style.color='blue'`
The first part is the property value and the second is the method of action.

Other examples to call a document object(s) and return an array are by using either `getElementsByName` or `getElementsByClassName`. One of the most used functions in DOM manipulation is `getElementById`.

Any part of the HTML can be manipulated by cancelling default actions, making image swaps or rotating slide shows with already preloaded images. This manipulation of the DOM is the creation of dynamic websites.

