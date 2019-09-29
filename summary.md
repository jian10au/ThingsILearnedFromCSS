# Things I learned From CSS

1. Box Model:

The width and height you set is, by default, only for the content area of an html element.

Every element has four area:
1. content
2. padding
3. border
4. margin

2. Constraint of box model:

The height and width of the div can control the content area size but it cannot control the inner text or image within that content area. If the inner text or img oversizes the content area, it is the property of text or the image itself determines how they are displayed in the page. 

3. Position property:

* Relative to viewport - position: fixed;
* Relative to normal page edge - position: static/relative/absolute;
1. relative means RELATIVE to its normal position;
2. absoluted means RELATIVE to its closest parent container. Notice, the parent container's position property also needs to be set to NON-STATIC to make the postion: absolute useful for its children. 
* Other - sticky;






