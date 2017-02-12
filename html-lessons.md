---
layout: default
---

[back](./)
<br />

# Html

## [](#header-1)About -
Html is **the _easiest_ language ever** and is as easy to read as english. It is the languages that is used to create websites and webpages and is read by browsers like internet explorer and safari or google chrome. Html's full form is
<br />
_HyperText **Markup** Language_
<br />
This means that HyperText is the internet, markup is used to style the content like underlining it or highlighting it and language is that web pages communicate through it.

<br />
<br />
<hr />
<hr />
### [](#header-3)Starting Html -
To start a html document, open any text editor such as notepad or text edit and save a file with a extension of .html
Then when you open the file, it will open your default browser and display what is inside the Html document. Right now there is nothing in it so it wont display anything.
<br />
<br />
<hr />
<br />

### [](#header-3)Putting stuff inside the Html document -

To put stuff in the Html document, right click and open with any text editor and first type in this code -
<br />

```
<html>
</html>
```

<br />

This code will tell the browser that the type of document it is reading is Html and not something else. Then the <html></html> code is where the Html document starts. All the main Html content is put between these tags.

<br />
<br />

Everything has a head and a body so add a head and body to the html document inside the <html></html> thing.

<br />

```
<html>
<head>
</head>
<body>
</body>
</html>
```

<br />
The <> and </> signs are used to define how the content in them is displayed on the screen like a big or small text or a hyperlink. Nearly everything has a duplicate in this Html document because Html nearly every html thing (element) has a opening **_tag_** and a closing **_tag_**.
<br />
This is done so that the browser knows when to stop the data inside the tags like a change of color or font size. The closing tag has a  / before the name of the tag.
<br />
<br />
IMPORTANT - In Html 5, a _!DOCTYPE html_ tag has to be put at the start of a document. It should be in between <> but I cant show it as it is not allowed in this language (github markdown).
<br />
<br />
<hr />
### [](#header-3)Adding content to the web page -
First a Header for the document is needed so add a header in the body of the html document like this -

<br />

```
<h1>My header</h1>
```

<br />
This will give a output of My header in a large font. The header can vary from 1 to 6 so -

<br />

```
<h1>Biggest Header</h1>
<h2>Bigger Header</h2>
<h3>Big Header</h1>
<h4>Small header</h4>
<h5>Smaller header</h5>
<h6>Smallest Header</h6>
```

<br />

These are the types of headers in Html.
<br />

With a header there has to be a paragraph so to add a paragraph to your page, do this -

<br />

```
<h1>My header</h1>
<p>A paragraph about my header</p>
```

<br />

The paragraph (<p></p>) tag has a smaller font size.
<br />
<hr />
<br />

### [](#header-3)Adding lists -
To add a list to a Html document, first think if you want numbers or points. Points are found in unordered lists (ul) and numbers are found in ordered lists(ol).
<br />
To use unordered and ordered lists add a <li></li> tag in them for a new point or number.
<br />
Unordered Lists -

<br />

```
<ul>My unordered list
<li>Point 1</li>
<li>Point 2</li>
<li>Point 3</li>
</ul>
```

<br />

To add ordered lists -

<br />

```
<ol>My ordered list
<li>Number 1</li>
<li>Number 2</li>
<li>Number 3</li>
</ol>
```

<br />
The <li></li> tag is used for both the lists so that when using css or styling, all li's can be changed in less typing. See the **_css_** lesson for that.
<br />
<hr />
<br />

### [](#header-3)Changing Appearance of Elements -

Elements in Html can look different if a little code is added in between the < and >. This piece of code except the element itself is known ad a attribute.
One of the most used attributes is the **style** attribute.
This is how to change the color of text using the style attribute in a paragraph -

<br />

```
<p style="color: blue;">My Blue paragraph</p>
```

<br />
This will change the color of the text to blue. The attribute's value is put inside double quotes "" .
<br />
The style attribute has a format (inside the double quotes) like this -

<br />

```
style-name: value;
```

<br />
The style name can be anything from like color (to change color) or font-family (to change type of font).
To change the font type and color and size, do this (in double quotes) -

<br />

```
color: red; font-family: cursive; font-size: 40px;
```

<br />
This will make the element's size as 40px, the font-family (font) as cursive and the color red.
<br />
To define alot of attributes add a semicolon (;) so that the computer knows that the command has stoped and that another one is starting.
