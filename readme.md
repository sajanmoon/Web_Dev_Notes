# Web Development

Web Development consists of building and maintaining websites. It is divided into two main parts:

## Frontend

- Focuses on layout, animations, and user interface.
- Technologies used:
  - HTML (HyperText Markup Language)
  - CSS (Cascading Style Sheets)
  - JavaScript
  - React

## Backend

- Focuses on server-side logic, database management, and debugging.
- Technologies used:
  - Node.js
  - Python
  - Java

---

# HTML (HyperText Markup Language)

HTML is a markup language used to structure web pages. It is not a programming language.

### Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Document Title</title>
  </head>
  <body>
    <h1>Welcome to Web Development</h1>
  </body>
</html>
```

### Important HTML Tags

#### Heading Tags

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

#### Paragraph Tag

```html
<p>This is a paragraph.</p>
```

### Formatting Tags

Refer to [W3Schools Formatting Guide](https://www.w3schools.com/html/html_formatting.asp)

```html
<b>Bold Text</b>
<i>Italic Text</i>
<u>Underlined Text</u>
<s>Strikethrough Text</s>
<ins>Inserted Text</ins>
<sup>Superscript (e.g., 2<sup>2</sup>)</sup>
<sub>Subscript (e.g., H<sub>2</sub>O)</sub>
<small>Small Text</small>
<mark>Highlighted Text</mark>
<strong>Important Text</strong>
<em>Emphasized Text</em>
```

---

# Forms in HTML

Forms are used to collect user input.

### Input Tags (Self-closing Tags)

```html
<input type="text" placeholder="Enter your name" />
<input type="number" max="10" min="1" />
<input type="password" placeholder="Enter password" />
<input type="date" />
<input type="time" />
<input type="radio" name="gender" value="male" /> Male
<input type="radio" name="gender" value="female" /> Female
<input type="checkbox" name="subscribe" /> Subscribe
<input type="submit" value="Submit" />
```

### Input Attributes

```html
<input type="text" name="username" />
<!-- Helps server understand the field -->
<input type="text" value="Default Value" />
<!-- Default input value -->
<input type="text" placeholder="This is a placeholder" />
<!-- Displays hint text -->
<input type="number" max="10" min="1" />
<!-- Restricts number input range -->
<input type="text" readonly value="Cannot edit this text" />
<!-- Read-only field -->
<input type="hidden" value="secret" />
<!-- Hidden field -->
```

### Dropdown (Select)

```html
<select>
  <option>Red</option>
  <option>Blue</option>
</select>
```

### iframe

- Used to embedded data from site or webpage to your own web page

```html
<iframe src="https://www.bing.com/" width="50%" height="300"></iframe>
```

- Youtube directly provide iframe

### Some of usecases of iframe

- Creating a seprate section or a page
- Displaying Ads
- embedding social media

- some website disable iframe for security reasons

### Image tage

```html
<img src="www.image.com" alt="image" />
<!-- here we are taking directly a image from a url -->
<img src="./images" alt="image" />
<!-- here we are taking image from our local machine -->
```

### Video tag

```html
<video controls width="400" height="400" loop muted autoplay>
  <source src="www.vide.com" />
</video>
```

### Audio tag

```html
<audio controls width="400" height="400" loop muted autoplay>
  <source src="www.audio.com" />
</audio>
```

## List tag

### ordered list

### unordered list

```html
<ol>
  <li>Red</li>
  <li>Yellow</li>
  <li>Green</li>
</ol>
<!-- in ordered list we will get a number to our list  -->

<ul>
  <li>Red</li>
  <li>Yellow</li>
  <li>Green</li>
</ul>
<!-- in unordered list we will get a bullet to our list  -->
```

## Table tag

```html
<table border="1" cellspacing="0">
  <!-- border : to add the border  -->
  <!-- cellspacing : to add or remove space between border  -->

  <!-- table head  -->
  <thead>
    <!-- table row -->
    <tr>
      <!-- table heading  -->
      <th>Contory</th>
      <th>litracy Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <!-- table data  -->
      <td align="center">India</td>
      <td>80%</td>
    </tr>
    <tr>
      <td>India</td>
      <td>80%</td>
    </tr>
    <tr>
      <td>India</td>
      <td>80%</td>
    </tr>
  </tbody>
  <!-- table footer  -->
  <tfoot>
    <tr>
      <td>world</td>
      <td>70%</td>
    </tr>
  </tfoot>
</table>
```

## Semantic tags

- Tags which have some meaning helps browser and SEO to identify components

```html
<header></header>
<footer></footer>
<nav></nav>
<article></article>
<form></form>
```

## Non-Semantic tags

- Tags which have nomeaning only use to structure ,layout ,style

```html
<div></div>
<span></span>
```

## Meta Tags

- Used for browser search engine

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
    <meta name="description" content="this is a description" />
    <meta name="authorship" content="" />
  </head>
  <body></body>
</html>
```

# css

## CSS Selectors

### Tag selectors

- Directly adding style to element eg h1, p ,span etc h1 { background-color:red}

### Class selectors

- Adding style to class eg class = name | .name{background-color : blue}

### ID selector

- For a unique element | id=name |#name{background-color:blue}

```

```
