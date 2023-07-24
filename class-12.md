# JavaScript Canvas:  
-HTML5 features the &lt;canvas> element that allows you to draw 2D graphics using JavaScript.  
-The &lt;canvas> element requires at least two attributes: width and height that specify the size of the canvas:  
ex: &lt;canvas width="500" height="300" id="canvas">&lt;/canvas>  
-you can access the width and height properties of the &lt;canvas> element via its DOM properties:  

const canvas = document.querySelector('#canvas');  
const width = canvas.width;// 500  
const height = canvas.height;// 300  
-And you can also change the width and height of the &lt;canvas> element using the DOM methods:  

canvas.width = 600;  
canvas.height = 400;  
-The &lt;canvas> element features the getContext() method that returns a render context object.  
-The getContext() takes one argument which is the type of context. For example, you use the "2d" to get a 2D rendering context object, which is an instance of the CanvasRenderingContext2D interface.  
-The 2D rendering context lets you draw shapes, text, images, and other objects.  
## Questions:  
1. What does the &lt;canvas> allow a developer to acheive?
-  it is used to obtain the rendering context and create a drawing context for the canvas.  
2. What is the importance of the closing `&lt;/canvas> tag?
Essential for defining the correct structure of the HTML document.  
3. Explain what the getContext() method does.  
-The getContext() method, used with the HTML5 &lt;canvas> element, allows you to obtain the drawing context (either 2D or WebGL) for the canvas, providing a set of methods and properties to draw graphics dynamically on the canvas, such as shapes, paths, text, and images. It is a crucial step in preparing the canvas for graphics rendering and manipulation using JavaScript.

# Chart.js Documentation:  
-Chart.js provides a set of frequently used chart types, plugins, and customization options.  
-Chart.js comes with a sound default configuration, making it very easy to start with and get an app that is ready for production.  
-Chart.js comes with built-in TypeScript typings and is compatible with all popular JavaScript frameworks including React , Vue , Svelte , and Angular . You can use Chart.js directly or leverage well-maintained wrapper packages that allow for a more native integration with your frameworks of choice.  
-Chart.js is very well suited for large datasets.  
## Questions:  
1.What is Chart.js and how it can be brought into your project?  
-Chart.js is a popular JavaScript library used for creating interactive and visually appealing charts and graphs on web pages. It provides an easy-to-use API to create various types of charts, such as bar charts, line charts, pie charts, and more. To bring Chart.js into your project, you can include the Chart.js library in your HTML file by adding a script tag that references the Chart.js library hosted either locally or through a content delivery network (CDN). Once included, you can then use Chart.js methods and configurations to create and customize charts within your web application.  
2.List 3 different Chart types you can create using Chart.js.  
-Line chart  
-Bar chart  
-Pie chart  
# Easily create stunning animated charts with Chart.js:  
-To start, you must download Chart.js  
-Then you need to copy the Chart.min.js out of the unzipped folder and into the directory youll be working in. After that, create a new html page and import a script found online.  
-There are ways draw a line chart, pie chart, and many other charts (online to reference these).  
## Questions:  
1.What are some advantages to displaying data via a chart over a table?
-Visual representation, simplified complexity, comparison and relationships, and accessibility amongst a few other things.  
2. How could Chart.js aid your previously created applications visually?  
-It could help with the Salmon cookies website by helping create the table that was needed for it!  

## Things I want to know more about:   
N/A  















