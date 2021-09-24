# HTML 
### Table of content
1. [About](##About)
2. [Syntax](##Syntax)
3. [Page Structure](##structure)
4. [creat a link](##link)
5. [table](##table)
6. [list](##list)
7. [**image maps**](#Maps)
8. [extended studies references](#Extended)
9. [extended of extended studies references](#extendedOFextended)

## About <a name="About"></a>
1. is a markup language
2. for creating webpage and doc
3. build blocks for website

4. use index.html as the root page
5. use .html extension

## Syntax `<tag> content </tag>` <a name="Syntax"></a>
````html
<strong> text </strong>
<i> text </i>
<u> text </u>
<b> text </b>
<blockquote> quote </blockquote>
````
Render Effect :
normal, 
<i> italic </i>, 
<strong> strong </strong>, 
<b> bold </b>, 
<u> underline </u>

<blockquote> halo, hello, hi </blockquote>

## Page structure <a name="structure"></a>
````html
<html>
	<head> 
		<title> Title of the page </title>
	</head>
````
````html	
	<body>
		<!-- can be h1 - h6  -->
		<h1> header 1<h1>	
		<p> paragraph 1</p>
	</body>
</html>
````
## Create a link  <a name="link"></a>
+ `target = "_blank" to open a new tab`
+ <a href="https://www.example.com/" target="_blank"> This is a link </a>

````html
<a href="https://www.example.com/" target="_blank"> This is a link </a>
````
## table <a name="table"></a>
`<table>`, 
`<thead> table header`, 
`<th> table head`, 
`<tbody> table body`, 
`<tr> table row`, 
`<td> table data`

we jz use table, tr, th, td

````html
<table>
		<tr>
			<th> head 1 </th>
			<th> head 2 </th>
		</tr>
		<tr>
			<td> row 1 data 1 </td>
			<td> row 1 data 2 </td>
		</tr>
		<tr>
			<td> row 2 data 1 </td>
			<td> row 2 data 2 </td>
		</tr>
</table>
````

Effect: 

<table>
		<tr>
			<th> head 1 </th>
			<th> head 2 </th>
		</tr>
		<tr>
			<td> row 1 data 1 </td>
			<td> row 1 data 2 </td>
		</tr>
		<tr>
			<td> row 2 data 1 </td>
			<td> row 2 data 2 </td>
		</tr>
</table>

## list <a name="list"></a>
### unordered list, ul
 
````html
	<ul>
		<li>item 1</li>
		<li>item 2</li>
	</ul>
````
<html>
	<ul>
		<li>item 1</li>
		<li>item 2</li>
	</ul>
</html>

### ordered list, ol
````html
	<ol>
		<li>item 1</li>
		<li>item 2</li>
	</ol>
````

<html>
	<ol>
		<li>item 1</li>
		<li>item 2</li>
	</ol>
</html>

# **Image Maps**  <a name="Maps"></a>

The HTML <map> tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more <area> tags.

````html
<img src="assert/image/002-html-example.PNG" alt="Workplace" usemap="#workmap">
<map name="workmap">
	<area shape="rect" coords="34,44,270,350" alt="Computer" 
		href="https://www.google.com/search?q=computer" target="_blank">
	<area shape="rect" coords="290,172,333,250" alt="Phone" 
		href="https://www.google.com/search?q=phone" target="_blank">
	<area shape="circle" coords="337,300,44" alt="Coffee" 
		href="https://www.google.com/search?q=coffee" target="_blank"	>
</map>
````

Try to click the laptop, phone or coffee below: `not clickable in gitlab`

<img src="assert/image/002-html-example.PNG" alt="Workplace" usemap="#workmap">
<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://www.google.com/search?q=laptop" target="_blank">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://www.google.com/search?q=phone" target="_blank">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="https://www.google.com/search?q=coffee" target="_blank">
</map>

# Extended studies <a name="Extended"></a>
### references at W3school

1. [html form](https://www.w3schools.com/html/html_forms.asp)
2. [html5 canvas](https://www.w3schools.com/html/html5_canvas.asp)
3. [html audio](https://www.w3schools.com/html/html5_audio.asp)
4. [html youtube](https://www.w3schools.com/html/html_youtube.asp)
5. [html geolocations](https://www.w3schools.com/html/html5_geolocation.asp)
6. [Drag and drop](https://www.w3schools.com/html/html5_draganddrop.asp)
7. [web storage](https://www.w3schools.com/html/html5_webstorage.asp)

### ADDITIONAL: go for css, javascript, sql, python and php
### ADDITIONAL:  canvas, svg

# ADDITIONAL STUDIES <a id="extendedOFextended"></a>

### 1. React
+ React is a JavaScript library for building user interfaces.
+ React is used to build single page applications.
+ React allows us to create reusable UI components.

### 2. jquery
+ jQuery is a lightweight, "write less, do more", JavaScript library.
+ The purpose of jQuery is to make it much easier to use JavaScript on your website.
+ jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish,
and wraps them into methods that you can call with a single line of code.
+ jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

### 3. node.js
+ Node.js is an open source server environment.
+ Node.js allows you to run JavaScript on the server.

### 4. angular js
+ AngularJS extends HTML with new attributes.
+ AngularJS is perfect for Single Page Applications (SPAs).
+ AngularJS is easy to learn.
