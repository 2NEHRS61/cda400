#Week 4

##Extending the knowledge of CSS selectors
-  Element names as selectors
	```html 
		p {   
     		color: red;
		}
	```
	
- 	If we want we can group selectors together. For instance, we might want all our headings to be grey

	```html 
		h1, h2, h3, h4, h5, h6 {
			color: grey;	
		} 
	
	```
	
- We can have class `.` and id selectors `#`

	```html 
	.section {
		font-size: 20px;
	}
	
	#footer  {
		font-size: 10px;
	}
	
	```	
	
##CSS Pseudo-elements
	
- Rather than having to apply class and id's to elements, we can save ourself time by targeting them using an elements children by using a `pseudo-element` 

	```html 
        h1:before {
          	content:url(smiley.gif);
           
       }
	
	```
	
	```html 
		p::first-letter {
    		color: #red;
    		font-size: xx-large;
      }
	
	```
	
##CSS Pseudo-classes

- We can use these CSS classes to add special effects to elements themselves or a special state of the element 




##CSS display Property

- CSS has two main ways of displaying elements
	-	`display: block`
- An image is a inline element by default, however often you want an image to display on it's own line. In this case we can change the `display` property to `block`
- For example, here's how we centre align an image:
	
	```html 
	.displayed {
		 display: block; 
	 }
	```
- We can then assign the display class to an image:

	```html
	<img class="displayed" src="..." alt="..."  />
	```
- We can also use the shorthand margin property to achieve the same result:

	```html
	img.displayed 
		   display: block;
	```
	
##Margins

- two values: 1st=top & bottom; 2nd=left & right, e.g. `margin:10px 5px;`

- four values: top, right, bottom and left, e.g. `margin:10px 5px 15px 20px;`

##Width and Height

	```html 
	 p {width: 40%;}
		
	```		 
	selector {
		position: <value>
	}

```

![](assets/static_divs.png)


#wrapper{

##Adding a float left 

````
#wrapper{

![](assets/floated_lef_divs.png)

##Adding a float to the left and right
#wrapper{
![](assets/floated_left_right_divs.png)