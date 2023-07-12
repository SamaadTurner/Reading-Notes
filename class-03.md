# HTML: HyperText Markup Language:  
*This is important because it is one of the main languages that we will be learning in this course!  

HTML is the most basic building block of the web.  
"Hypertext" refers to links that connect web pages to one another.  
HTML uses "markup" to annotate text, images, and other content for display in the browser.  

# Order List:  

The &lt;ol> HTML element represents an ordered list of items.  
-typically rendered as a number list.  

ex: 

&lt;ol>
  &lt;li>Mix flour, baking powder, sugar, and salt.&lt;/li>  
  &lt;li>In another bowl, mix eggs, milk, and oil.&lt;/li>  
  &lt;li>Stir both mixtures together.&lt;/li>  
  &lt;li>Fill muffin tray 3/4 full.&lt;/li>  
  &lt;li>Bake for 20 minutes.&lt;/li>  
&lt;/ol>  

output:  

Mix flour, baking powder, sugar, and salt.  
In another bowl, mix eggs, milk, and oil.  
Stir both mixtures together.  
Fill muffin tray 3/4 full.  
Bake for 20 minutes.  

# Unordered List:  

The &lt;ul> HTML element represents an unordered list of items, typically rendered as a bulleted list.  

ex:  

&lt;ul>  
    &lt;li>Milk&lt;/li>  
    &lt;li>Cheese  
        &lt;ul>  
            &lt;li>Blue cheese&lt;/li>  
            &lt;li>Feta&lt;/li>  
        &lt;/ul>  
    &lt;/li>  
&lt;/ul>  

output:  

Milk  
Cheese  
  Blue cheese  
  Feta  

# Questions:  

When should you use an unordered list in your HTML document?  
-When you want to store multiple items in no order.  

How do you change the bullet style of unordered list items?  
-Use CSS. Apply the 'list-style-type' property to the  '&lt;ul>' or '&lt;li>' element and set the desire value. 

When should you use an ordered list vs an unorder list in your HTML document?  
-You should use an ordered list (&lt;ol>) in your HTML document when you want to display a list of items in a specific sequential order, such as steps in a process, rankings, or a chronological timeline.   
On the other hand, you should use an unordered list (&lt;ul>) when the order of the items is not important, and you simply want to present a collection of items without any particular sequence or hierarchy,  
such as bullet points, options, or a list of related but equally significant items.  

Describe two ways you can change the numbers on list items provided by an ordered list?  
-changing the numbering style or starting the numbering from a specific value.  


# Learn CSS:  

CSS is used to style it and lay out your html document.


# Questions:  

Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?  
-In the story titled "The Box Model," the CSS properties of margin and padding take on the roles of two characters: Margina and Paddington. Margina, with her ability to set margins, creates space and separation between elements, bringing order to the design. Paddington, on the other hand, adds cushioning and comfort with his padding magic. Together, they navigate the world of the box model, ensuring proper spacing and delightful user experiences by adjusting margins and adding padding to elements within the story.  

List and describe the four parts of an HTML elements box as referred to by the box model.  
1.content. nnermost part of the box and contains the actual content, such as text, images, or other HTML elements.  
2.padding. The padding surrounds the content and provides space between the content and the border.   
3.border. The border is a line that surrounds the padding and content, creating a visible boundary for the element.   
4.margin. The margin is the outermost part of the box and provides space between the element and its surrounding elements.  

# JavaScript:  

JavaScript is a programming language that allows you to implement complex functionalities on web pages.  

# Questions:  

What data types can you store inside of an Array?  
-any  

Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?  
-Yes, the people array provided is a valid JavaScript array. To access the values stored in the array, you can use array indexing.  

List five shorthand operators for assignment in javascript and describe what they do.  
1. += - the addition assignment adds the value on the right side to the variable on the left side and the results back to the variable.  
2. -= - subtracts the value on the right-hand side from the variable on the left-hand side and assigns the result back to the variable.  
3. *= - multiplies the variable on the left-hand side by the value on the right-hand side and assigns the result back to the variable.  
4. /= - divides the variable on the left-hand side by the value on the right-hand side and assigns the result back to the variable.  
5. %= - calculates the remainder when the variable on the left-hand side is divided by the value on the right-hand side and assigns the result back to the variable.

Read the code below and evaluate the last expression and explain what the result would be and why.    
-The last expression (a + c) + b would result in a string concatenation.   
In JavaScript, when you use the + operator with a string, it performs string concatenation instead of addition.  
In this case, the expression first evaluates (a + c) which results in the numeric addition of 10 and false, yielding 10 (since false is coerced to 0 in numeric context).  
Then, the resulting number 10 is concatenated with the string 'dog', resulting in the string '10dog'.  
Therefore, the result of the expression (a + c) + b would be the string '10dog'.  

Describe a real world example of when a conditional statement should be used in a JavaScript program  
-A real-world example of when a conditional statement should be used in a JavaScript program is in an online shopping application. When a customer adds items to their cart, a conditional statement can be used to check if the cart is empty. If it is, a message can be displayed to prompt the customer to add items. On the other hand, if the cart is not empty, the application can proceed to the checkout process. The conditional statement helps provide a personalized user experience based on the state of the cart.  

Give an example of when a Loop is useful in JavaScript.  
-A loop in JavaScript is useful in scenarios such as processing a collection of items. For instance, in a social media application, a loop can be utilized to iterate through a user's posts and display them on their profile page. This allows for efficient and automated handling of multiple posts without having to write repetitive code for each individual post.  










    

