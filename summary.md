# Things I learned From CSS

1. Box Model:

The width and height you set is, by default, only for the content area of an html element.

Every element has four area:
1. content
2. padding
3. border
4. margin

Bonus: add padding from the parent or add margin to children if I want to create some white space? 
Answer: visually, by itself, there is no real difference between this two options. BTW, set the position of an element is better handle by position property.

2. Constraint of box model:

The height and width of the div can control the content area size but it cannot control the inner text or image within that content area. If the inner text or img oversizes the content area, it is the property of text or the image itself determines how they are displayed in the page. 

3. Position property:

* Relative to viewport - position: fixed;
* Relative to normal page edge - position: static/relative/absolute;
1. relative means RELATIVE to its normal position;
2. absoluted means RELATIVE to its closest parent container. Notice, the parent container's position property also needs to be set to NON-STATIC to make the postion: absolute useful for its children. 
3. position relative will keep its the element's original position unchanged, while position absolute takes out the original element of the flow completely.
* Other - sticky;

4. CSS Selector:

 . notion - class
 '# notion - id
  without # or . - element in html

  starts with parent and then children. Parent or Child can be any three of above element. And the combination is wihtout any limitation. 




5. CSS inheritance - some css property does not inherit from parent's property at all



