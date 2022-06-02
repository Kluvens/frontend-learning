# HEML

## Basics
HTML stands for HyperText Markup Language:
- A markup language is a computer language that defines the structure and presentation of raw text.
- In HTML, the computer can interpret raw text that is wrapped in HTML elements.
- HyperText is text displayed on a computer or device that provides access to other text through links, also known as hyperlinks. You probably clicked on a couple of hyperlinks on your way to this Codecademy course.\

### HTML documents
All HTML documents must start with a document type declaration: ```<!DOCTYPE html>```.

The HTML document itself begins with ```<html>``` and ends with ```</html>```.

The visible part of the HTML document is between ```<body>``` and ```</body>```.

### HTML headings
HTML headings are defined with the ```<h1>``` to ```<h6>``` tags.
```<h1>``` defines the most important heading. ```<h6>``` defines the least important heading

### HTML paragraphs
HTML paragraphs are defined with the ```<p>``` tag
e.g. ```<p>This is a paragraph.</p>```

### HTML links
HTML links are defined with the ```<a>``` tag
e.g. ```<a href="https://www.w3schools.com">This is a link</a>```

In the example above, setting the ```target``` attribute to "```_blank```" instructs the browser to open the relevant Wikipedia page in a new window.
e.g. ```<a href="https://en.wikipedia.org/wiki/Brown_bear" target="_blank">The Brown Bear</a>```

### HTML images
HTML images are defined with the ```<img>``` tag.

The source file (```src```), alternative text (```alt```), ```width```, and ```height``` are provided as attributes

e.g. ```<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">```

### HTML attributes
The ```alt``` attribute: The required ```alt``` attribute for the ```<img>``` tag specifies an alternate text for an image, if the image for some reason cannot be displayed.
e.g. ```<img src="img_typo.jpg" alt="Girl with a jacket">``` this example contains two attributes: ```src``` and ```alt```.

The ```title``` attribute: The ```title``` attribute defines some extra information about an element.
e.g. ```<p title="I'm a tooltip">This is a paragraph.</p>```

Tips:
- always use lowercase attributes
- always quote attribute values
- double quotes are the most common in HTML

### HTML text formatting
- ```<b>``` - Bold text
- ```<strong>``` - Important text
- ```<i>``` - Italic text
- ```<em>``` - Emphasized text
- ```<mark>``` - Marked text
- ```<small>``` - Smaller text
- ```<big>``` - Bigger text
- ```<del>``` - Deleted text
- ```<ins>``` - Inserted text
- ```<sub>``` - Subscript text
- ```<sup>``` - Superscript text

### HTML quotation and citation
- ```<blockquote>``` - defines a section that is quoted from another source.
- ```<q>``` - defines a short quotation which inserts double quotation marks.
- ```<abbr>``` - defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
- ```<address>``` - defines the contact information for the author/owner of a document or an article.
- ```<cite>``` - defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

### HTML comments
```<!-- Write your comments here -->```

### HTML CSS
```<link rel="stylesheet" href="styles.css">``` this connects to css file called styles.css

### HTML table
- ```<table>``` - defines an HTML table
- ```<tr>``` - defines table row
- ```<th>``` - defines table header
- ```<td>``` - defines table cell
- ```<tbody>``` - long tables can be sectioned off using the table body element
- ```<thead>``` - table heading can be sectioned off using the table heading element
- ```<td colspan="2">Out of Town</td>``` - spanning(merging) columns
- ```<td rowspan="2">Work</td>``` - spanning(merging) rows

### HTML list
- ```<ul>``` - defines an unordered list
- ```<ol>``` - defines an ordered list
- ```<li>``` - defines each item
- ```<dl>``` - defines description list
- ```<dt>``` - defines the term (name)
- ```<dd>``` - describes each term

### HTML block and inline elements
- ```<div>``` - defines a division or a section in an HTML document, this is vertical to other text. - (block-level)
- ```<span>``` - is an inline container used to mark up a part of a text, or a part of a document. - (inline)

### HTML id attribute
The HTML ```id``` attribute is used to specify a unique id for an HTML element.

You cannot have more than one element with the same id in an HTML document.

**difference between class and id:**
A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page

