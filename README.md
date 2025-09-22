Basics of HTML and CSS

HTML (HyperText Markup Language) is used to structure content on the web, while CSS (Cascading 
Style Sheets) is used to style and design it. Together, they form the backbone of modern web 
development.

HTML Basics:
HTML documents are made of elements wrapped in tags.Common tags include:

1. Document Structure
<!DOCTYPE html> → Defines the HTML5 document type.
<html> → Root element of an HTML page.
<head> → Contains metadata, title, links, scripts.
<title> → Page title (appears in browser tab).
<body> → Main content of the page.

2. Text Formatting
<h1> to <h6> → Headings (largest to smallest).
<p> → Paragraph.
<b> / <strong> → Bold text.
<i> / <em> → Italic/emphasized text.
<u> → Underlined text.
<small> → Smaller text.
<mark> → Highlighted text.
<br> → Line break.
<hr> → Horizontal line.

3. Lists
<ul> → Unordered list (bullets).
<ol> → Ordered list (numbers).
<li> → List item.

4. Links & Media
<a href="url"> → Hyperlink.
<img src="img.jpg" alt="text"> → Image.
<audio controls> → Audio player.
<video controls> → Video player.
<iframe> → Embed external content (e.g., YouTube).
<map> <area> → group and define clickable area.

5. Tables
<table> → Defines a table.
<tr> → Table row.
<th> → Table header.
<td> → Table data cell.

6. Miscellaneous 
<section> → Section of content.
<div> → Block-level container.
<span> → Inline container.
<pre> → Preformatted text.
<link> → Link external files (CSS).
<meta> → Metadata (charset, viewport).

CSS Basics:
CSS is used to style HTML. It works via:
Inline CSS → <p style="color:red">
Internal CSS → <style> p{color:red;} </style>
External CSS → <link rel="stylesheet" href="style.css">

1. Selectors
* → Universal.
p, h1, div → Element selectors.
.classname → Class selector.
#idname → ID selector.
parent child → Descendant.
element:hover → Pseudo-class.
::before, ::after → Pseudo-elements.

2. Text & Font
color
font-family
font-size
font-weight
text-align
text-transform
line-height
letter-spacing
text-decoration

3. Box Model
width, height
margin
padding
border
box-sizing

4. Backgrounds
background-color
background-image
background-repeat
background-size
background-position
background-attachment

5. Positioning
position: static | relative | absolute | fixed | sticky
top, left, right, bottom
z-index

6. Display & Layout
display: block | inline | inline-block | flex | grid | none
overflow: hidden | scroll | auto
float
clear

7. Flexbox
display: flex
justify-content
align-items
flex-wrap
flex-direction
gap

8. Grid
display: grid
grid-template-columns
grid-template-rows
grid-gap

9. Colors & Gradients
Named colors (red, blue).
HEX (#ff0000).
RGB (rgb(255,0,0)).
HSL (hsl(0,100%,50%)).
