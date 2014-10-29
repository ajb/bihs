BIHS Script Ed Notes Sept-Oct
====

## Syntax

- An html document is made up of `<tags></tags>`
- Different tags define how the page is rendered and denotes the larger structure of the page.

### There are two types of tags
1. Self closing - tags that do not have any nested content. ex `<img src="someimg.png" />`
2. Tags which require an `<open>` tag and a `</open>` closing tag. These tags typically have nested content: `<p> This is a very short paragraph </p>`

### Attributes
Aside from the tag name, some tags will have attributes. These attributes can help define the tag and how itâ€™s displayed, they are additional data about the tag they are applied to. 

ex: `<img class="big-image" src="someimg.png">`

## Basic HTML page structure
```html
<!DOCTYPE html> // tells the browser what version of HTML you are coding in
<html>
<head> // information about the page goes here and link to external files such as CSS and JS
<title>The Title of the Page</title>
</head>
<body>
  // your content will go in between the body tags of your html
</body>
</html>
```

> Note: // in HTML indicates a comment, the browser will not render anything on the same line as the comment.

## Content Tags
Tags that allow you to display content, be it text or images, on an HTML page.

### Heading Elements
Denotes importance based on the level applied:

```html
<h1>Largest Heading</h1>
<h2>...</h2>
<h3>...</h3>
<h4></h4>
<h5></h5>
<h6>Smallest Heading</h6>
```

### Text Elements
```html
<p>This is a paragraph</p>
<code>This is some computer code</code>
<ul>Unordered list</ul>
```

### Anchor (link) tag 
```html
<a href="file or link you are referencing" alt="description of link" target="how the browser opens the link">
  Information about the link (usually) the name of the site
</a>

<a href="generalassemb.ly" alt="General Assemblyâ€™s website." target="_blank">
  General Assembly
</a>
```

### Heading
- `<h1> Usually the main title of the page, or most important information you want your visitors to see</h1>`
- Heading tags range from `<h1>` to `<h6>` and the font for each heading gets smaller and smaller.

### Paragraph 
- `<p>this is a paragraph</p>`

### Div
- `<div>This is a div. Itâ€™s used to group chunks of information together.</div>` 

### Nav 
- `<nav>This is the navigation of your site (list of links, like â€œHome", â€œAbout", â€œContact".</nav>`

### Break-line
- `<br />` breaking space in the document (does not need a closing tag)

### Horizontal rule 
- `<hr />` inserts a line to separate sections of the document (does not need a closing tag)

### Emphasis 
- `<em> Used to add italics to text </em>`

### Strong 
- `<strong> Used to bold text</strong>`

### Code 
- `<code> displays HTML as text so the browser will not attempt the run the code </code>`

### Unordered list  
```html
<ul> <!-- unordered list tag -->
        <li>Item 1</li> <!-- list item -->
        <li>Item 2</li>
        <li>Item 3</li>
</ul>
```

### Ordered list
```html
<ol> <!-- ordered list -->
    <li>Item 1</li>
</ol>
```

### Self-closing Tags
Some tags are self-closing, meaning they open and close in the same tag.

```html
<img src="images/puppy.jpg" />
```

## CSS

CSS is a language that lets us change the _style_ of our webpages.

We write CSS inside of `<style>` tags in the `<head>` of our webpage:

```
...
<head>
  <style>
    h1 {
      color: blue;
    }
  </style>
</head>
...
```

### Components of CSS

Using the example above:

- `h1`: the _selector_. It selects the HTML elements that our styles will get applied to.
- `color`: the _property_. There are many different properties, including color, background-color, font-size, etc.
- `blue`: the _value_. The format of the value depends on the `property` that it is for.


## Resources

- [HTML Elements](http://www.w3schools.com/html/html_elements.asp)
- [HTML Attributes](http://www.w3schools.com/html/html_attributes.asp)
- [List of CSS Properties](http://www.w3schools.com/cssref/)
