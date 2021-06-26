## Object Literals

 > Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names


## WHAT IS AN OBJECT? 

1- JavaScript object is a standalone entity that holds multiple values in terms of properties and methods.
2-JavaScript object is a standalone entity that holds multiple values in terms of properties and methods.
3-An object can be created using object literal or object constructor syntax.
4-Object literal:
`var person = { 
    firstName: "James", 
    lastName: "Bond", 
    age: 25, 
    getFullName: function () { 
        return this.firstName + ' ' + this.lastName 
        } 
};`

5-Object constructor:
`var person = new Object();                
person.firstName = "James";
person["lastName"] = "Bond"; 
person.age = 25;
person.getFullName = function () {
        return this.firstName + ' ' + this.lastName;
    };`

6-Object properties and methods can be accessed using dot notation or [ ] bracket.
7-An object is passed by reference from one function to another.
8-An object can include another object as a property.
\

### Object initializer
Objects can be initialized using new Object(), Object.create(), or using the literal notation (initializer notation). An object initializer is a comma-delimited list of zero or more pairs of property names and associated values of an object, enclosed in curly braces ({}).

![object](https://1.bp.blogspot.com/-eHICkeDNwmg/XInHyvSvIVI/AAAAAAAAACs/VaP1WfL3LhYs2DgMxmdaLaq0F6bD_HCPACLcBGAs/s1600/definig%2Bwith%2Bkey%2Bvalue%2Bpair.JPG)

--------------------------------------------------------------

### Document Object Model

#### The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.

#### What is the DOM?

**The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.**

![Dom](https://www.w3schools.com/js/pic_htmltree.gif)

#### ACCESSING ELEMENTS :anger:

DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes. 


>Sometimes you will just want to access one
individual element (or a fragment of the page that
is stored within that one element). Other times you
may want to select a group of element s, for example,
every \<hl> element in the page or every <1 i>
element within a particular list. 

>Here, the DOM tree shows the body of the page of
the list example. We focus on accessing elements
first so it only shows element nodes. The diagrams
in the coming pages highlight which elements a
DOM query would return. (Remember, element
nodes are the DOM representation of an element.)

![ACCESSING ELEMENTS](https://cdn.codecoda.com/themes/user/site/default/asset/img/blog/html-scheme.png)

### SELECTING ELEMENTS USING ID ATTRIBUTES 

##### Using The id Attribute

The id attribute specifies a unique id for an HTML element. The value of the id attribute must be unique within the HTML document.

The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.

The syntax for id is: write a hash character (#), followed by an id name. Then, define the CSS properties within curly braces {}.

In the following example we have an \<h1> element that points to the id name "myHeader". This \<h1> element will be styled according to the #myHeader style definition in the head section:


### LOOPING THROUGH A NODELIST 


##### Loop over a nodelist
Use the ES6 spread operator. [... elements]. forEach(function(ele) { ... ...
Use the Array methods. // `Array.from` is not supported on IE. Array. from(elements). ...
Use the forEach method. If you don't have to support Internet Explorer, then use the forEach method: elements.
