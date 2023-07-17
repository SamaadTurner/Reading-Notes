# Domain Modeling:  
-The process of creating a conceptual model in code for a specific problem.  
-A model decribes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain.  
-An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.  

## Question:  
1. Explain why we need domain modeling.   
-It provides clear understanding of the problem domain.

# HTML BASICS:  
-A table is a structured set of data made up of rows and columns. A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data.  
-The point of a table is that it makes things easy to look up (hence the columns and rows)...  
-You should not use a table to lay out web pages.  
- To add headers to tables you have to access the different cells in the top and side (for row and column you want to head) by using 'document.getElementById'.  
- you can make the table cells span multiple rows and columns by making them more interactive. To do so, use the colspan and rowspan words.


## Questions:  
1. Why should tables not be used for page layouts?
-Layout tables reduce accessibility for visually impaired users, tables produce tag soup, and tables are not automatically responsive.

2. List and describe 3 different semantic HTML elements used in an HTML &lt;table>:
- &lt;thead>, &lt;tbody, and &lt;tfoot> : elements used to group table's content into distinct sections for the table header, body, and footer.
- &lt;colgroup, &lt;col>, and &lt;colgroup> : elements allows you to group and style columns within a tables.
- &lt;caption> : element is used to provide a caption or title for the table.

# Introducing Constructors:  
-A constructor is just a function called using the new keyword. When you call a constructor, it will: create a new object, bind this to the new object so you can refer to this in your constructor code, run the code in the constructor, and return the new object.  
- Constructors start with a capital letter and are named for the type of object they create.
  EX: function Person(name) {  
  this.name = name;  
  this.introduceSelf = function () {  
    console.log(`Hi! I'm ${this.name}.`);  
  };  
}  
To call Person() as a constructor, we use new:  
const salva = new Person("Salva");  
salva.name;  
salva.introduceSelf();  
// "Hi! I'm Salva."  

const frankie = new Person("Frankie");  
frankie.name;  
frankie.introduceSelf();  
// "Hi! I'm Frankie."  

## Questions:  
1.What is a constructor and what are some advantages to using it?  
- A constructor is a special method or function in object-oriented programming that is used to initialize objects of a class.
  Some advantages of using it are object initialization and encapsulation.
2. How does the term this differ when used in an object literal versus when used in a constructor?
  - In an object literal, 'this' refers to the current object that is being defined. It represents the object itself, allowing you to access and modify its properties and methods. In a constructor, 'this' refers to the newly created object instance. It represents the specific instance being created and allows you to assign values to its properties.

# Object Prototypes Using A Constructor:  
- Objects are key/value pairs. The most common way to create an object is with curly braces {} and you add properties and methods to an object using dot notation.  

let animal = {}  
animal.name = 'Leo'  
animal.energy = 10  

animal.eat = function (amount) {  
  console.log(`${this.name} is eating.`)  
  this.energy += amount  
}  

animal.sleep = function (length) {  
  console.log(`${this.name} is sleeping.`)  
  this.energy += length  
}  

animal.play = function (length) {  
  console.log(`${this.name} is playing.`)  
  this.energy -= length  
}  

-prototype is just a property that every function in JavaScript has and it allows us to share methods across all instances of a function. All our functionality is still the same but now instead of having to manage a separate object for all the methods, we can just use another object that comes built into the Animal function itself.  

## Question:  
1. Explain prototypes and inheritance via an analogy from your previous work experience.
   -In my previous work experience, prototypes can be likened to a template or blueprint that defines the common characteristics and behaviors of a product line, while inheritance is akin to a new product inheriting those traits and functionalities from the prototype, allowing for efficient development and maintenance by reusing existing code.

   ## Things I want to know more about:  
   -prototypes  












