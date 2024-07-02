# What is HTML?

- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

## Qs What is rendering?

In programming, "rendering" refers to the process of generating a visual representation of data. It is commonly used in the context of:

- Web Development: Rendering HTML, CSS, and JavaScript to display web pages in a browser.

- Graphics Programming: Converting 3D models into 2D images or animations.

- UI/UX Design: Drawing the user interface elements on the screen based on the application's state.

- Document Rendering: Converting documents (like PDFs) into a visual format for display.

Rendering involves taking raw data or code and transforming it into a visual format that users can interact with or view.

OR

Rendering in programming refers to processing any piece of code that we have written and showing the result of it.

## CSS

- Style: Sets the look and feel.
- Colors & Fonts: Customizes text and background.
- Layout: Controls position and size.
- Selectors: Targets specific HTML elements.

## Javascript

- Actions: Enables interactivity.
- Updates: Alters page without reloading.
- Events: Responds to user actions.
- Data: Fetches and sends info to server.

## Importance of index.html file

- Default name of a website's homepage.
- First page users see when visiting a website.
- Important for SEO.
- Provides uniform starting point across servers.
- Servers as fallback when no file is specified in URL.

Tags and Attributes are not case sensitive in HTML. Recommended to use lowercase.

### Attributes

- Attributes provide additional information about elements.
- Placed within opening tags.
- Common examples: href, src, alt.
- Use name=value format.
- Can be single or multiple per element.

### id property

- Unique Identifier: Each id should be unique within a page.
- Anchoring: Allows for direct links to sections using the #id syntax in URLs.
- CSS & Javascript: Used for selecting elements for styling or scripting.

#### pre tag

- Preserves text formatting.
- Maintains whitespace and line breaks.
- Useful for displaying code.

### Semantic/Non Semantic Tags

- A semantic element clearly describes its meaning to both the browser and the developer.

- Examples of non-semantic elements: ``` <div> and <span> ``` - Tells nothing about its content.
  
- In HTML there are some semantic elements that can be used to define different parts of a web page:  

```-
<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>
```

- Examples of semantic elements: ``` <form>, <table>, ```  and ``` <article> ``` - Clearly defines its content.

## HTML Structure

```-
<body>
    <header></header>
    <main>
        <section><section/>
        <section><section/>
        <aside></aside>
        ...
    </main>
    <footer></footer>
</body>
```

### Folder Structure

```_
-root_Directory
    -index.html
    -html_directory (for other html pages)
    -css_directory 
    -scripts_directory (for javascript)
    -images_directory (for images)
    -assets_directory (other assets like font can go in this folder)
    -sub_directory
```

#### Navigation Tag

The ```<nav>``` HTML element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.

```_
<nav class="crumbs">
  <ol>
    <li class="crumb"><a href="#">Bikes</a></li>
    <li class="crumb"><a href="#">BMX</a></li>
    <li class="crumb">Jump Bike 3000</li>
  </ol>
</nav>

<h1>Jump Bike 3000</h1>
<p>
  This BMX bike is a solid step into the pro world. It looks as legit as it rides and is built to polish your skills.
</p>
```

### HTML Block and Inline Elements

A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

Two commonly used block elements are: ```<p>``` and ```<div>```.

The ```<p>``` element defines a paragraph in an HTML document.

The ```<div>``` element defines a division or a section in an HTML document.

Here are the block-level elements in HTML:

```_
<address>
<article>
<aside>
<blockquote>
<canvas>
<dd>
<div>
<dl>
<dt>
<fieldset>
<figcaption>
<figure>
<footer>
<form>
<h1>-<h6>
<header>
<hr>
<li>
<main>
<nav>
<noscript>
<ol>
<p>
<pre>
<section>
<table>
<tfoot>
<ul>
<video>
```

#### Inline Elements

An inline element does not start on a new line.

An inline element only takes up as much width as necessary.

This is a ```<span>``` element inside a paragraph.

Here are the inline elements in HTML:

```_

<a>
<abbr>
<acronym>
<b>
<bdo>
<big>
<br>
<button>
<cite>
<code>
<dfn>
<em>
<i>
<img>
<input>
<kbd>
<label>
<map>
<object>
<output>
<q>
<samp>
<script>
<select>
<small>
<span>
<strong>
<sub>
<sup>
<textarea>
<time>
<tt>
<var>
```

### HTML List Tags

Tag Description

```<ul>```: Defines an unordered list

```<ol>```: Defines an ordered list

```<li>```: Defines a list item

```<dl>```: Defines a description list

```<dt>```: Defines a term in a description list

```<dd>```: Describes the term in a description list.

#### Unordered HTML List - Choose List Item Marker

The CSS list-style-type property is used to define the style of the list item marker. It can have one of the following values:

```disc```: Sets the list item marker to a bullet (default)

```circle```: Sets the list item marker to a circle

```square```: Sets the list item marker to a square

```none```: The list items will not be marked

```_
<ul style="list-style-type:disc;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

### Table Tag

A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data, for example a person and their age, or a day of the week, or the timetable for a local swimming pool.

HTML Table Tags

```<table>```: Defines a table

```<th>```: Defines a header cell in a table

```<tr>```: Defines a row in a table

```<td>```: Defines a cell in a table

```<caption>```: Defines a table caption

```<colgroup>```: Specifies a group of one or more columns in a table for formatting

```<col>```: Specifies column properties for each column within a ```<colgroup>``` element

```<thead>```: Groups the header content in a table

```<tbody>```: Groups the body content in a table

```<tfoot>```: Groups the footer content in a table.

## HTML Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing.

### The ```<input>``` Element

The HTML ```<input>``` element is the most used form element.

An ```<input>``` element can be displayed in many ways, depending on the type attribute.

Here are some examples:

```<input type="text">```: Displays a single-line text input field

```<input type="radio">```: Displays a radio button (for selecting one of many choices)

```<input type="checkbox">```: Displays a checkbox (for selecting zero or more of many choices)

```<input type="submit">```: Displays a submit button (for submitting the form)

```<input type="button">```: Displays a clickable button.

### The ```<label>``` Element

Notice the use of the ```<label>``` element in the example above.

The ```<label>``` tag defines a label for many form elements.

The ```<label>``` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focuses on the input element.

The ```<label>``` element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the ```<label>``` element, it toggles the radio button/checkbox.

The for attribute of the ```<label>``` tag should be equal to the id attribute of the ```<input>``` element to bind them together.

## HTML class Attribute

The HTML class attribute is used to specify a class for an HTML element.

Multiple HTML elements can share the same class.
The class name is case sensitive!

## HTML id Attribute

The HTML id attribute is used to specify a unique id for an HTML element.

You cannot have more than one element with the same id in an HTML document.

The id name is case sensitive!

Note: The id name must contain at least one character, cannot start with a number, and must not contain whitespaces (spaces, tabs, etc.).

## Difference Between Class and ID

A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page.

## HTML File Paths

A file path describes the location of a file in a web site's folder structure.

### File Path Examples

```<img src="picture.jpg">```: The "picture.jpg" file is located in the same folder as the current page.

```<img src="images/picture.jpg">```: The "picture.jpg" file is located in the images folder in the current folder.

```<img src="/images/picture.jpg">```: The "picture.jpg" file is located in the images folder at the root of the current web.

```<img src="../picture.jpg">```: The "picture.jpg" file is located in the folder one level up from the current folder.

### Absolute File Paths

An absolute file path is the full URL to a file:

```<img src="https://www.w3schools.com/images/picture.jpg" alt="Mountain">```

### Relative File Paths

A relative file path points to a file relative to the current page.

In the following example, the file path points to a file in the images folder located at the root of the current web:

```<img src="/images/picture.jpg" alt="Mountain">```

## HTML - The Head Element

The HTML ```<head>``` element is a container for the following elements: ```<title>```, ```<style>```, ```<meta>```, ```<link>```, ```<script>```, and ```<base>```.

## The HTML \<head\> Element

The ```<head>``` element is a container for metadata (data about data) and is placed between the ```<html>``` tag and the ```<body>``` tag.

HTML metadata is data about the HTML document. Metadata is not displayed.

Metadata typically define the document title, character set, styles, scripts, and other meta information.

## The HTML \<meta\> Element

The ```<meta>``` element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.

The metadata will not be displayed on the page, but is used by browsers (how to display content or reload page), by search engines (keywords), and other web services.

### Examples

- Define the character set used:

  ```<meta charset="UTF-8">```

- Define keywords for search engines:

  ```<meta name="keywords" content="HTML, CSS, JavaScript">```

- Define a description of your web page:

  ```<meta name="description" content="Free Web tutorials">```

- Define the author of a page:

  ```<meta name="author" content="John Doe">```

- Refresh document every 30 seconds:

  ```<meta http-equiv="refresh" content="30">```

- Setting the viewport to make your website look good on all devices:

  ```<meta name="viewport" content="width=device-width, initial-scale=1.0">```

### Setting The Viewport

The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.

You should include the following ```<meta>``` element in all your web pages:

```<meta name="viewport" content="width=device-width, initial-scale=1.0">```

This gives the browser instructions on how to control the page's dimensions and scaling.

The ```width=device-width``` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The ```initial-scale=1.0``` part sets the initial zoom level when the page is first loaded by the browser.

- The ```<head>``` element is a container for metadata (data about data)

- The ```<head>``` element is placed between the ```<html>``` tag and the ```<body>``` tag

- The ```<title>``` element is required and it defines the title of the document

- The ```<style>``` element is used to define style information for a single document

- The ```<link>``` tag is most often used to link to external style sheets

- The ```<meta>``` element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings

- The ```<script>``` element is used to define client-side JavaScripts

- The ```<base>``` element specifies the base URL and/or target for all relative URLs in a page.

## Responsive Images

Responsive images are images that scale nicely to fit any browser size.

### Using the width Property

If the CSS width property is set to 100%, the image will be responsive and scale up and down.

```<img src="img_girl.jpg" style="width:100%;">```

Notice that in the example above, the image can be scaled up to be larger than its original size. A better solution, in many cases, will be to use the max-width property instead.

### Using the max-width Property

If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size:

```<img src="img_girl.jpg" style="max-width:100%;height:auto;">```

## Show Different Images Depending on Browser Width

The HTML ```<picture>``` element allows you to define different images for different browser window sizes.

```_
<picture>
  <source srcset="img_smallflower.jpg" media="(max-width: 600px)">
  <source srcset="img_flowers.jpg" media="(max-width: 1500px)">
  <source srcset="flowers.jpg">
  <img src="img_smallflower.jpg" alt="Flowers">
</picture>
```

## Responsive Text Size

The text size can be set with a ```"vw"``` unit, which means the ```"viewport width"```.

```<h1 style="font-size:10vw">Hello World</h1>```

Viewport is the browser window size. 1vw = 1% of viewport width. If the viewport is 50cm wide, 1vw is 0.5cm.

## Media Queries

In addition to resize text and images, it is also common to use media queries in responsive web pages.

With media queries you can define completely different styles for different browser sizes.

```_
<style>
.left, .right {
  float: left;
  width: 20%; /* The width is 20%, by default */
}

.main {
  float: left;
  width: 60%; /* The width is 60%, by default */
}

/* Use a media query to add a breakpoint at 800px: */
@media screen and (max-width: 800px) {
  .left, .main, .right {
    width: 100%; /* The width is 100%, when the viewport is 800px or smaller */
  }
}
</style>
```

## HTML Entities

Reserved characters in HTML must be replaced with entities:

```_
< (less than) = &lt;
> (greather than) = &gt;
```

### HTML Character Entities

Some characters are reserved in HTML.

If you use the less than ```(<)``or greater than```(>)```signs in your HTML text, the browser might mix them with tags.

Entity names or entity numbers can be used to display reserved HTML characters.

- Entity names look like this:

  ```&entity_name;```

- Entity numbers look like this:

  ```&#entity_number;```

To display a less than sign ```(<)``` we must write: ```&lt;``` or ```&#60;```

Entity names are easier to remember than entity numbers.

## Some Useful HTML Character Entities

```_
  non-breaking space       &nbsp;    &#160;
< less than                &lt;      &#60;
> greater than             &gt;      &#62;
& ampersand                &amp;     &#38;
" double quotation mark    &quot;    &#34;
' single quotation mark    &apos;    &#39;
¢ cent                     &cent;    &#162;
£ pound                    &pound;   &#163;
¥ yen                      &yen;     &#165;
€ euro                     &euro;    &#8364;
© copyright                &copy;    &#169;
® trademark                &reg;     &#174;
```

### Non-breaking Space

A commonly used HTML entity is the non-breaking space: ```&nbsp;```

A non-breaking space is a space that will not break into a new line.

Two words separated by a non-breaking space will stick together (not break into a new line). This is handy when breaking the words might be disruptive.

Another common use of the non-breaking space is to prevent browsers from truncating spaces in HTML pages.

If you write 10 spaces in your text, the browser will remove 9 of them. To add real spaces to your text, you can use the &nbsp; character entity.
