# JavaScript Object basics  
-an object is a collection of related data and/or functionality. These usually consist of several variables and functions.    
-an object is made up of multiple members, each of which has a name and a value.  
-each name/value pair must be seperated by a comma, and the name and value in each case are seperated by a colon.  
const objectName = {    
  member1Name: member1Value,  
  member2Name: member2Value,  
  member3Name: member3Value,  
  };  
  Objects literal:  
-A way to create an object directly specifying its properties and values within curly braces.  
## Dot Notation:  
-A way to access and manipulate properties and methods of an object.  
## Bracket Notation:  
-An alternative way to access and manipulate properties and methods of an object. It involves using square brackets with the property or method name as a string inside the brackets to access the desired element within the object.  
Ex: const person = {  
name: "name"  
age: 30  
-Ex:  
const person = {  
  name: "John",  
  age: 30,  
  city: "New York"  
};  

console.log(person["name"]); // Output: John  

## Constructors:  
-A constructor is a special type of function used to create and initialized objects. It serves as a blueprint or template for creating multiple instances of objects with similar properties and behaviors.  
-Heres an ex:  
function Person(name, age) {  
  this.name = name;     
  this.age = age;    
}  

// Creating new instances using the constructor  
const john = new Person("John", 30);  
const sarah = new  

# Questions:  

1. How would you describe an object to a non-technical friend you grew up with?    
-An object is like a container that holds information or characteristics about something. It's a way to represent and work with things in the digital world, just like a toy or tool represents something in the real world.  
2. What are some advantages to creating object literals?  
-Overall, object literals offer simplicity, readability, flexibility, and independence, making them a powerful tool for creating and initializing objects in JavaScript.
3. How do objects differ from arrays?  
-Objects store data as key-value pairs and are accessed by keys, providing a way to represent entities with specific attributes. Arrays store data as an ordered collection of elements and are accessed by numeric indices, useful for storing and accessing a list of related items.
4.Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
-when iterating over an object's properties using a loop or accessing properties with special characters or spaces in their names.
5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
-refers to the object itself, which is the 'dog'. The advantage of using 'this' is that allows the method to access and refer to the specific properties of the object it is part of.

# Introduction To The DOM:  

-Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.  
-It is a programming interface or web documents. It represents the page so that programs can change the doc structure, style, and content.  
-The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts.  

# Questions:  
1. What is the DOM?
-The DOM (Document Object Model) is a programming interface for HTML and XML documents. It represents the structure of a web page as a tree-like structure of objects, where each element, attribute, and text node in the HTML document becomes a node in the DOM tree.
2.Briefly describe the relationship between the DOM and JavaScript.  
-The DOM and JavaScript have a close relationship as JavaScript is the primary language used to interact with and manipulate the DOM. JavaScript provides methods and properties to access and modify elements, attributes, and content of the DOM, allowing dynamic behavior, event handling, and updates to web pages based on user actions or other programmatic triggers.

## Things I want to know more about  
-DOM and its connectivity to javaScript.  












