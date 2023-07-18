# FlexBox:  
-Flexbox is a layout mechanism designed for laying out groups of items in one demension.  
-Things you can do with flexbox: It has the following features:  
 -display as a row, or column, respects the writing mode of the document, they are single line by default, but can be asked to wrap onto mulitple lines,
 items in the layout can be visually reordered, and away from their order in the DOM.   
 -the main axis follows your flex-direction.  
## Creating a flex container:    
&lt;div class="container" id="container">  
  &ltdiv>One&lt/div>  
  &ltdiv>Item two&lt/div>  
  &ltdiv>The item we will refer to as three&lt/div>  
&lt/div>  
- To use flexbox you need to declare that you want to use a flex formatting context and not regular block and inline layout. Do this by changing the value of the display property to flex.
 - ex:  
    .container {    
  display: flex;  
}    
## Controlling the direction of items:  
-There hasnt been a flex-direction property added yet in the above code, the items do display as a row (because it was set). To change the property and one of the four values, do one of these:    
row: the items lay out as a row.  
row-reverse: the items lay out as a row from the end of the flex container.  
column: the items lay out as a column.  
column-reverse : the items lay out as a column from the end of the flex container.  

## Questions:   
1. Flexbox is designed for one-dimensional content. Explain what this means.
   - focuses on organizing elements in a linear direction, either horizontally or vertically, with the ability to dynamically adjust their size and position based on available space.
2. Explain the difference between the main axis and cross axis.
   - The main axis represents the primary direction in which items are laid out, The cross axis, on the other hand, is perpendicular to the main axis and runs in the opposite direction.
3. How can using certain properties of flexbox negatively impact accessibility?
   -The can affect accessbility. For an example, the row-reverse and column-reverse are reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.
   
## The flex-flow shorthand:  
-Able to set the flex-direction and flex-wrap properties using the shorthand flex-flow. For example, to set flex-direction to column and allow items to wrap:  
.container {  
  display: flex;  
  flex-flow: column wrap;  
}


## Questions:  
1. What are some advantages of using flexbox over float?
   -  Flexbox offers better control over alignment and spacing, allowing for easy centering and equal distribution of items. It eliminates the need for clearing floats and avoids the associated complexities.
2. How does this topic connect with your long term goals?
   - this connects with my longterm goal because I will be having to position things in the future on websites and here is another way to do it.
   - 







