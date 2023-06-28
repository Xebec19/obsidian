HTML Fundamentals and Building a Basic Webpage

Hi, This week we will cover HTML and some of its important tags

### What is HTML
HTML is the standard markup language for creating Web pages.
eg
```
<!DOCTYPE html>  
<html>  
<head>  
<title>Page Title</title>  
</head>  
<body>  
  
<h1>My First Heading</h1>  
<p>My first paragraph.</p>  
  
</body>  
</html>
```

You can refer below article regarding how to run a html file locally in your browser [link](https://www.w3schools.com/html/html_editors.asp)

Some important tags
1. Heading
   HTML headings are defined with the `<h1>` to `<h6>` tags.

	`<h1>` defines the most important heading. `<h6>` defines the least important heading:
	
```
<h1>This is heading 1</h1>  
<h2>This is heading 2</h2>  
<h3>This is heading 3</h3>	
```

2. Paragraphs
   HTML paragraphs are defined with the `<p>` tag:
```
<p>This is a paragraph.</p>  
<p>This is another paragraph.</p>
```

3. Links
   HTML links are defined with the `<a>` tag:
```
<a href="https://www.w3schools.com">This is a link</a>
```
The link's destination is specified in the `href` attribute. 
Attributes are used to provide additional information about HTML elements.

4. Images
   HTML images are defined with the `<img>` tag.
```
<img src="pic_trulli.jpg" alt="Italian Trulli">
```

We can also define width and height image
```
 <img src="html5.gif" alt="HTML5 Icon" width="128" height="128">
```

5. Favicon
   A favicon is a small image displayed next to the page title in the browser tab.
```
<link rel="icon" type="image/x-icon" href="/images/favicon.ico">   
```

6. Title
   The `<title>` element adds a title to your page:
```
<!DOCTYPE html>  
<html>  
<head>  
  <title>HTML Tutorial</title>  
</head>  
<body>  
  
The content of the document......  
  
</body>  
</html>   
```

7. Tables
   HTML tables allow web developers to arrange data into rows and columns.
```
<table>  
  <tr>  
    <th>Company</th>  
    <th>Contact</th>  
    <th>Country</th>  
  </tr>  
  <tr>  
    <td>Alfreds Futterkiste</td>  
    <td>Maria Anders</td>  
    <td>Germany</td>  
  </tr>  
  <tr>  
    <td>Centro comercial Moctezuma</td>  
    <td>Francisco Chang</td>  
    <td>Mexico</td>  
  </tr>  
</table>   
```

Rowspan and Colspan
https://www.w3schools.com/html/html_table_colspan_rowspan.asp

8. Forms
   Very important! https://www.w3schools.com/html/html_forms.asp
   input fields and button
   
Good to know
1. Comments in html
	<!-- Write your comments here -->


