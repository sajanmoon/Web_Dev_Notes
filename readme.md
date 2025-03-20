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

- Directly adding style to element eg h1, p ,span etc

```html
<h1>hello</h1>
h1 { background-color:red}
```

### Class selectors

- Adding style to class eg

```html
<h1 class="name">hello</h1>
.name{background-color : blue}
```

### ID selector

- For a unique element

```html
<h1 id="name">hello</h1>
#name{background-color:blue}
```

### Decendent Selector (eg .container p)

```html
<div class="container">
  <p>This paragraph is inside the div.</p>
</div>

<p>This paragraph is outside the div.</p>

.container p { color: blue; font-weight: bold; }
```

- The paragraph inside .container turns blue & bold.
- The paragraph outside remains unchanged.

### Child Selector (eg h1 > p)

```html
<div class="container">
  <p>This is a direct child.</p>
  <div>
    <p>This is a nested child.</p>
  </div>
</div>
.container > p { color: red; font-weight: bold; }
```

- ✅ The first <p> (direct child) turns red & bold.
- ❌ The second <p> (nested inside another <div>) remains unchanged.

### Adjacent sibling Tag (eg h1 + p)

- it select the first sibling of a tag and add a styling to it
- for eg if have h1 and p tag in html and we wrote h1+p it will apply style to the p tag only (direct sibling)

```html
<h1>hello</h1>
<p>qwertyuip</p>

h1 + p { background-color:red }

<!-- Here the style will apply to p tag  -->
```

### Genral sibling selector (eg h1 ~ p)

- same as a adjacent but here it will select all the sibling tag add a style to it

## Psuedo Selector ( :hover)

- :hover (when we take mouse over the element)

- :active (only for the time of click)

- :visted (after click it changes)

- :focus (used in input tag when we click on it it stared working)

- :nth-child(1) (if we have multiple h1 the umber we pass there will be the style applied)

- :first-Child select first child

- :last-Child select last child

## Psuedo Element

- add styling to specific element

- ::before (the content applies before the element)

- ::after (the content applies after the element)

- ::first-line (if we have a paragraph it will apply style to first line)

- ::first-letter (if we have a sentence it will apply style to first letter)

### Attribute Selector (input[type="text"])

- eg input[type="text"] it will add a style specific to it

## Font Style

```html
<p class="styled-text">This is a beautifully styled paragraph.</p>
.styled-text { font-size: 20px; /* Sets the font size */ font-weight: bold; /*
Makes the text bold */ font-style: italic; /* Makes the text italic */
font-family: Arial, sans-serif; /* Sets the font family */ color: #2c3e50; /*
Dark blue-gray text color */ text-transform: uppercase; /* Converts text to
uppercase */ letter-spacing: 2px; /* Increases space between letters */
text-shadow: 2px 2px 5px gray; /* Adds a text shadow */ }
```

## Float

- to give a style like a newspaper article

```html
img { width: 200px; float: right; } .clear { clear: right; }
```

# JAVASCRIPT

- To add a funtionality to our website we need javascript

- To add a javascript to html we need script tag
- for external javascript file add src in script tag

- Three ways to write in javascript
- console log ("hello world)
- document . write("hello world")
- alert ("hello world")

## Variables

- const num = 4
- const(declaration key) num(Value Name) = 4(Variable value)
- we can check the data type by typeof ---- const data = (typeof 4)

### Differnt Variable

- There are 3 differnt ways to declare variable - var,let,const

### Var

- Can be redeclare
- var is a global scope
- var is not block scoped
- var is a functional scope

### Let

- Can be reassign
- let is a global scope
- let is block scope
- let is a functional scope

### const

- Cannot be redeclare or reassign
- const is a global scope
- const is a block scope
- const is a functional scope

## Scopes

- Block Scope (let and const)
- Function Scope (var)
- Globaal Scope (var,let,const)

# Data Types

- string
- number
- boolean
- null
- undefined

# Operators

- Artimetic (+,-,/)
- Assignment (=,+=,-=)
- logical (&& (And), || (or),!(not) )
- Comparison (== , === , != , !== , > , <)

# Condition

- if
- if else

# Loops

```html
- for(initiliation;condition;increment/decrement)
<br />
{ code to be executed } - for (let i = 0; i < 5; i++) { console.log(i); }
```

### While Loop

```html
let i = 1; while (i <= 10) { console.log(i); i++; }
```

# Arrays

### Array Methid

- Push - Add a element to the end of a array
- Pop - Remove a element to the end of a array
- unshift - Add an element to the end of the array
- shift - Remove an elemnt to the the end of the array

### Array Loop

- for loop

let basket = ["mango", "banana", "papaya", "watermelon"];

- for (let i = 0; i <=basket.length; i++)
- { console.log(basket[i]); }

## JavaScript Loop Example

The following JavaScript code iterates over an array of fruits and logs each item to the console:

```javascript
let basket = ["mango", "banana", "papaya", "watermelon"];

for (let items of basket) {
  console.log(items);
}
```

```html

```

```

```
