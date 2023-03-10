# Head, Title, Body


```html
<!DOCTYPE html> 
<html lang="en-US"> 
    <head> 
        <meta charset="UTF-8"> 
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Page Title</title> 
    </head> 
    <body> 
        <!-- Your HTML content goes here --> 
    </body> 
</html>
```

`<!DOCTYPE>`declaration tells the browser that it is a html5 document.

In html there are 3 main things according to me: 

![html](https://user-images.githubusercontent.com/69891912/222506176-81664258-a623-43b1-ad8f-872e8d05e067.png)

- element or a tag (opening tag, closing tag and self-closing tag)
- attribute 
- value of that attribute

The HTML document itself begins with `<html>` and ends with `</html>`

`lang="en-US"` tells the browser that the language of the page is english and US country.

`<head>` is the section that is not visible on the page but contains following elements: 
`<title>`, `<style>`, `<meta>`, `<link>`, `<script>`, and `<base>`

`title` element determines what browsers show in the title bar or tab for the page.

`<style>` element is stylesheet code -> CSS code.

`<meta chatset="UTF-8">` tells the browser about multiple languages. This ensures that text in different languages will be displayed correctly in the browser.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">` defines the viewport for responsive design. This tag is important for making sure the website looks good on all devices, including mobile devices.

`<script>` is the element used to add javascript code.

`<body>` contains all the content that is shown on the page.

# Text related

`<h1> <h2> <h3> ... <h6>` is for headings

`<p>` is used for paragraph

`<em>`  used to emphasize text

`<i>` for itallic text

`<b>` used for bold text

The `<br/>` tag defines a line break, and is an empty element without a closing tag.

`<small>` makes text smaller

`<del>` makes the text cut by a line from the middle

`<sub>` tag or Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for formulas, like: <p>H<sub>2</sub>O</p>

`<ins>` shows the inserted text.

`<q>` tag defines a short quotation.

`<bdo>` tag is used to override the current text direction and change it to right to left

The value of the title attribute will be displayed as a tooltip when you mouse over the element. For example: 
```html
<p title="I'm a tooltip">This is a paragraph.</p>
```

`<sup>` element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Like:
<p>a<sup>2</sup>+b<sup>2</sup>+ 2ab = (a+b)<sup>2</sup></p>

`<hr>` element is called Horizontal Rule and is used to separate content (or define a change) in an HTML page.

`<br>` to get a new line without starting a new paragraph

# Links related

`<a>`called anchor is used for links
example - `<a href="https://www.w3schools.com">This is a link</a>`

The link's destination is specified in the `href` attribute. 

`target ="_blank"` attribute used for opening link in new tab

```html
`<a href="https://www.w3schools.com" target="_blank">This is a link</a>`
```

Nesting can also be done like:
```html
<p> This is a paragraph <a href =""> and this is a link </a> text </p>
```

# Images related

`<img>` for images 

example - `<img src="URL of image" alt="alternate text">` where src is the source of image.

All `img` elements should have an `alt` attribute. The `alt` attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.
```html
<img src="https://" alt="alternate text" width="x" height="y">
```
(where x and y could be pixels, em, rem, percentage etc values)

There are two ways to specify the URL in the `src` attribute:

**- Absolute URL** - Links to an external image that is hosted on another website. Example: "https://www.w3schools.com/images/img_girl.jpg".

**- Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. 
Example: src = "img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

**Tip:** It is almost always best to use relative URLs. They will not break if you change domain.

# Main 

The `<main>` tag in HTML is used to define the main content of a web page. It is intended to be unique to the document and to exclude content that is repeated across a set of documents such as site **navigation, header, or footer.** The purpose of using a `<main>` tag is to improve accessibility and provide a better structure to the HTML document.

# Section

The `<section>` tag in HTML defines a specific section of a web page, such as a header, footer, or content area. It is used to group related content together.

Note: When you add a lower rank heading element to the page, it's implied that you're starting a new subsection.

# List items

Use list item (`li`) elements to create items in a list. Here is an example of list items in an unordered list:

```html
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```

## Span

`<span>` tag is an inline element used to group and apply styles to a small piece of content within a larger block of text or a container. Basically to target a small piece of text inside a div.

Some common uses of the **`<span>`** tag include:

1. Applying CSS styles to a specific part of a text or element.
2. Highlighting a word or phrase within a paragraph or sentence.
3. Adding custom data attributes to an element, which can be used to store metadata or perform other functions in JavaScript.

