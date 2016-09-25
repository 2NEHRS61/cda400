
# Session 1 

- [What is HTML](#what-is-html)
- [Tools used To Create HTML Pages](#tools-used-to-create-html-pages)
- [HTML Elements](#html-elements)
- [HTML Attributes](#html-attributes)
- [HTML Comments](#html-comments)



##What is HTML?

 ![html 5 logo](assets/html5_logo.png)   
>> [We're on HTML version 5](https://www.w3.org/TR/html5/)   

- Hyper Text Markup Language
- File extension, needs to be .html or .htm

##Tools Used To Create HTML Pages

![html 5 logo](assets/brackets.jpeg)  
>> [We recommend using Brackets](http://brackets.io/)  


- Basic text editors
- We highly recommend you use <strong> brackets </strong> for this course

##HTML Elements 

- An HTML document is made up of elements also know as HTML tags
	- An html document starts with the doctype `<!DOCTYPE html>`
	- The rest of the document is nested in-between  `<html>` tags

- HTML tags are enclosed in < brackets:

```html  
<tagname>content</tagname>  
```	

An complete HTML document example:


```html
<!DOCTYPE html>

```

[Read W3 Schools for an introduction to different tags](http://www.w3schools.com/html/html_intro.asp)


Let's breakdown the above example in some more detail:

- `<html> .. </html>` - all of the information is embedded between these tags

- `<head>...</head>` - contains descriptive information about the content to come
	- 	`<title>..</title>` - as it sounds, it is the title for the page

- `<body>...</body>` - The main content of the document 
- `<p>..</p>` -  a paragraph tag to hold a paragraph of text
-  	<a>...</a> -  this is a how we create a hyperlink, anything between the two hyperlink tags will be clickable 


##HTML Attributes

- Each element may have one or more attributes
  provide additional information about elements
  specified in the start tag
  
- Attributes come in name/value pairs like: name="value"

- Below, we use attributes to specify the source of an image and where a link should point to
  
  
```html
<img src="image.jpg" alt="describe the image" />
<a href="http://www.solent.ac.uk">University</a>

```

##HTML Comments 

HTML comments allow you to embed statements into an html which won't be shown to the user


```html
	<!-- this is an html comment -->

```


	







  