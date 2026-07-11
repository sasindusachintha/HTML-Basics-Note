# HTML-Basics-Note
A beginner-friendly collection of HTML examples, syntax guides, and best practices for learning web development.

---

# What is HTML?
- HTML stands for Hyper Text Markup Language.
- HTML describes the structure of a Web page.

---

# A Simple HTML Document
``` </pre>
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph is this one.</p>

</body>
</html>
``` 
---

# HTML Elements
``` </pre>
Start tag	 Element content	      End tag
<h1>	     My First Heading	      </h1>
<p>	         My first paragraph.	  </p>
<br>         none	                  none
```

---

# HTML Headings
HTML headings are defined with the h1 to h6 tags.
``` </pre>
<h1>This is heading 1</h1>
```

---

# HTML Paragraphs
HTML paragraphs are defined with the p tag.
``` </pre>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

--- 

# HTML Links
HTML links are defined with the a tag:
``` </pre>
<a href="https://www.w3schools.com">This is a link</a>
```

---

# HTML Images
HTML images are defined with the img tag.
The source file (src), alternative text (alt), width, and height are provided as attributes:
``` </pre>
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```

---

# HTML Attributes
- All HTML elements can have attributes.
- Attributes provide additional information about elements.
- Attributes usually come in name/value pairs like: name="value".
Ex :- href, src, The width and height, The alt, style, lang, title,

- All HTML elements can have attributes
- The href attribute of <a> specifies the URL of the page the link goes to
- The src attribute of <img> specifies the path to the image to be displayed
- The width and height attributes of <img> provide size information for images
- The alt attribute of <img> provides an alternate text for an image
- The style attribute is used to add styles to an element, such as color, font, size, and more
- The lang attribute of the <html> tag declares the language of the Web page
- The title attribute defines some extra information about an element.

---

HTML Styles
The HTML style attribute is used to add styles to an element.

<tagname style="property:value;">

Example:
<p style="color:red;">This is a red paragraph.</p>

Common properties:
color
background-color
font-size
text-align

---

HTML Formatting
HTML provides elements for formatting text:

<b>Bold text</b>
<strong>Important text</strong>
<i>Italic text</i>
<em>Emphasized text</em>
<mark>Marked text</mark>
<small>Smaller text</small>
<del>Deleted text</del>
<ins>Inserted text</ins>
HTML Comments

Comments are not displayed in the browser.

<!-- This is a comment -->
HTML Colors

Colors can be specified using:

Color names (red, blue)
HEX values (#ff0000)
RGB values (rgb(255,0,0))

Example:

<p style="color:blue;">This is blue text</p>

---

HTML CSS
CSS is used to style HTML elements.

Inline CSS:

<p style="color:red;">Red text</p>

Internal CSS:
<style>
p {
  color: blue;
}
</style>

External CSS:

<link rel="stylesheet" href="styles.css">
HTML Lists
Unordered List
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
Ordered List
<ol>
  <li>First</li>
  <li>Second</li>
</ol>
HTML Tables
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>20</td>
  </tr>
</table>
HTML Forms

Forms are used to collect user input.

<form>
  Name: <input type="text"><br>
  Password: <input type="password"><br>
  <input type="submit">
</form>

Common input types:

text
password
email
radio
checkbox
submit
HTML Block vs Inline Elements
Block Elements
Takes full width
Starts on new line

Examples:

<div>, <p>, <h1>
Inline Elements
Takes only necessary width
Does not start on new line

Examples:
<span>, <a>, <img>
HTML Div and Span
Div (Block)
<div>This is a block container</div>
Span (Inline)
<span>This is inline</span>
HTML Semantic Elements

Semantic elements clearly describe their meaning.
Examples:
<header>
<nav>
<section>
<article>
<footer>
HTML File Structure Summary
<!DOCTYPE html>
<html>
<head>
<title>Title</title>
</head>
<body>

Content goes here
</body>
</html>
Final Note

HTML is the foundation of web development.
It works together with:

CSS → Styling
JavaScript → Functionality
