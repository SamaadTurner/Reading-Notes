# How the Web Works
This topic matters because it is the basis of this course...

Article provides a simple view of what happens when a webpage is viewed in a web browser on your computer or phone.   
Computers connected to the internet are called clients and servers. Clients are usually web user's internet-connected devices.  
Servers are usually computers that store webpages, sites, or apps.  
Internet Connection: Allows you to send and recieve data on the web.  
TCP/IP: Both are communication protocols that define how data should travel across the internet.  
DNS: Like an address book for websites.   
HTTP: An application protocol that defines a language for clients and servers to speak to each other.  
Component files: A webstie is made up of different files. Two types of the files: Code files (HTML, CSS, JavaScricpt) and Assets (A collective name for all the other stuff that makes up a website like images, music, video, etc.)  
Order in which component files are parsed: Browsers send requests to servers for HTML files (which contain a <link> elements) referencing external CSS stylesheets and <script> element refrencing external JavaScript scripts.  
The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.  
As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.  
The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.  
As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.  

# What will your website look like?
This topic matters because it is the basis of this course...

What should your website be about?  
What information are you presenting on the subject?  
What does your website look like in simple high-level terms?  
Sketching out your design: On paper.  
Choosing your assets: text, theme color, images, font.  

# JavaScript basics
This topic matters because it is the basis of this course...

JavaScript is a programming language that adds interactivity to a website.  
Comments are snippets of text that can be added along with code. The browser ignores text marked as comments.   
You can write comments in JavaScript just as you can in CSS: "/* , */".  

# Short Poem
Like a river's current, it flows and cascades,
Across networks vast, through tangled braids,
Packets of data, in bytes and strings,
HTTP's magic, the melody it sings.

# JavaScript basics Cont.
Describe how HTML, CSS, and JS files are “parsed” in the browser:  
HTML: The browser begins by parsing the HTML file, which defines the structure and content of the web page. It reads the HTML document from top to bottom, starting with the opening "<html>" tag and ending with the closing "</html>" tag. During this process, the browser identifies various elements such as headers, paragraphs, images, links, 
and more.  
As the HTML is parsed, the browser constructs a tree-like structure called the Document Object Model (DOM). The DOM represents the hierarchical relationship between different HTML elements, with the "<html>" tag as the root and nested elements as branches and leaves. This tree structure allows the browser to understand how the elements are organized on the page.
CSS: After the HTML parsing is complete, the browser moves on to parse the CSS (Cascading Style Sheets) files associated with the web page. CSS defines the presentation and layout of the HTML elements. The browser reads the CSS files and matches the styles to the corresponding HTML elements.  
During CSS parsing, the browser creates a separate structure known as the CSS Object Model (CSSOM). This model represents the styles defined in the CSS files, including properties like color, font, size, positioning, and more. The CSSOM is then combined with the DOM to create a Render Tree.  
JS: If the web page includes JavaScript files, the browser proceeds with parsing and executing them. JavaScript adds interactivity and dynamic behavior to the web page. When parsing JavaScript, the browser identifies functions, variables, loops, and other constructs and builds an abstract syntax tree (AST).  
Once the parsing is complete, the browser executes the JavaScript code, manipulating the DOM and CSSOM as needed. JavaScript can modify the content, style, and behavior of the web page, allowing for dynamic updates and interactivity.  
By parsing HTML, CSS, and JavaScript files, the browser creates the necessary structures (DOM, CSSOM, and AST) and combines them into a Render Tree. The Render Tree represents the final layout of the web page, including all visible elements, their styles, and the hierarchy in which they appear. Finally, the browser uses the Render Tree to render and display the web page on the user's screen.  
How can you find images to add to a Website?  
Google images  
How do you create a String vs a Number in JavaScript?  
let myString = "Hello, World!"; OR let myString = "Hello, World!";  
What is a Variable and why are they important in JavaScript?  
In programming, a variable is a named container or storage location used to store data.   Variables in JavaScript are important becaause they serve as the building blocks of programs, allowing for data storage, manipulation, reusability, and interactivity. They provide the flexibility and power required to create dynamic and functional applications.  

# Introduction to HTML
This topic matters because it is the basis of this course...  

What is an HTML attribute:   
extra information about the element that wont appear in the context.  

Describe the Anatomy of an HTMl element:  
Starts with an opening tag followed by the element name followed by attributes followed by the content followed by self-closing tag followed by closing tag.  
Together, these components form the structure of an HTML element, defining its type, attributes, content, and boundaries. HTML elements can be nested inside each other to create a hierarchical structure, allowing for the construction of complex web pages.  

What is the Difference between "&lt;article>" and "&lt;section>" element tags?  
The <article> element represents a self-contained, complete, and independently distributable composition within a document. It typically encapsulates content that could be considered a standalone entity, such as a blog post, news article, forum post, or a product description. It should make sense on its own and be meaningful even when extracted from the surrounding context.
The "<section>" element defines a thematic grouping of content within a document. It represents a standalone section or a logical block of related content that forms part of a larger whole. It doesn't carry the same standalone significance as an "<article>" but provides a way to organize and structure content based on a common theme or topic.  

What Elements does a “typical” website include?  
Header, navigation menu, hero section, content sections, footer, contact information, call-to-action buttons, social media integration, images and media, footer navigation.  

How does metadata influence Search Engine Optimization?  
Metadata plays a crucial role in Search Engine Optimization (SEO) by providing valuable information to search engines about the content and context of web pages.   

How is the "<meta>" HTML tag used when specifying metadata?  
The "<meta>" HTML tag is used to specify various types of metadata about an HTML document. It provides information to browsers and search engines but is not displayed directly to website visitors. The "<meta>" tag is typically placed within the "<head>" section of an HTML document.  

# Miscellaneous
How to start to design a website:  

What is the first step to designing a Website?
The first step to designing a website is to clarify its purpose and define the goals and objectives you want to achieve with the website.  

What is the most important question to answer when designing a Website?  
what is the goal an purpose of this website?  

Semantics:  

Why should you use an "&lt;h1>" element over a <span> element to display a top level heading?
Semantic Meaning, SEO Benefits, and accessibility.  

What are the benefits of using semantic tags in our HTML?  
Leveraging semantic tags in HTML promotes accessibility, search engine optimization, maintainability, consistency, scalability, and future compatibility, resulting in well-structured and user-friendly websites.  

What is Javascript?  

Describe 2 things that require JavaScript in the Browser?
Form Validation and Dynamic Content and interaction.  

How can you add JavaScript to an HTML document?  
Inline JavaScript.  




##Things I want to know more about



