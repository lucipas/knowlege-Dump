[Link]([Building Your First Web Page - Learn to Code HTML & CSS (shayhowe.com)](https://learn.shayhowe.com/html-css/building-your-first-web-page/))
#ShayHowe 

## terms

- *HTML* - HyperText Markup Language
	- elements
		- designator of *Structure & context* of objects.
		-  (i.e) `<h1>`
	- tags
		- <> that surround the element 
		- usually comes in beginning (`<opening tag>`) and end (`</closing tag>`)
	- attributes
		- value pairs that add information about an element.
		- (i.e) `<a href="Attribute"></a>`
- *CSS* - Cascading Style Sheets
	- Selectors
		- What grabs elements to be styled.
		- (e.g) element { ... }
	- Properties
		- The different styles that can be applied to an element
	- Values
		- Determines how properties are applied to a selector






## HTML
```html
<!DOCTYPE html>

<!-- Document type Declaration-->
<!-- Shows Browsers that this is HTML-->

<html lang="en">
<!-- Denotes beginnning of HTML Document-->
<head>
<!-- Holds Metadata about this HTML document-->
	<meta charset="utf-8">
	<!-- Shows the browser what characters to use-->
	<title></title>
	<!-- What is renders in the Tab-->
	<link rel="stylesheet" href="file/to/css">
	<!-- Adds the CSS to style HTML-->
</head>
<body>
<!-- Holds ELements to be rendered-->
</body>
</html>
```

## Cascading Style Sheets
```css
	element {
		property: value;
	}
	/*Type Selectors*/
	/*Selects target elements by their type.*/
	element { ... }
	/*Class Selector*/
	/*Selects target elements by their class*/
	/* selects <div class="class">*/
	.class { ... }
	/*ID Selector*/
	/*Selects target elements by their ID*/
	/* selects <div id="id" >*/
	#id{ ... }
	
```



## To Read
- [Common HTML terms](http://www.scriptingmaster.com/html/HTML-terms-glossary.asp) via Scripting Master
- [CSS Terms & Definitions](http://www.impressivewebs.com/css-terms-definitions/) via Impressive Webs
- [CSS Tools: Reset CSS](http://meyerweb.com/eric/tools/css/reset/) via Eric Meyer
- [Normalize.css](http://necolas.github.io/normalize.css/) via Nicolas Gallagher
