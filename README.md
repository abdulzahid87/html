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
