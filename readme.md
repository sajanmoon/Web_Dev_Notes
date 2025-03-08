# Wev Devlopment

- Web means [internet], Devlopment means [building something]
- Divided in two parts

## Frontend

- Focuses on layout, animation, etc
- Javascript,html,css,react

## backend

- Focuses on building code, debugging, database mangment
- nodejs,python,java

# HTML

- Hyper Text Markup Language
- it is a markup language and not a programing language used to how the website should be stuctured

- <!DOCTYPE html> (Used as an identifier for a document type tell this is a html

  file) - [html] tag from where HTML is starting and ending - two types of tag
  head and body - [Head] tag used to give information about document - [Body]
  visible content of a document ## Tags in HTML -
  <h1>
    used for heading ,varies from h1 to h6 -
    <p>
      ## Formating Tags - W3school link for refrence:
      https://www.w3schools.com/html/html_formatting.asp -
      <b>
        bold tag -
        <i>
          italic tag - <> underline tag -
          <s> strike tag - a line over a text </s> -
          <ins> inserted tag to add a inserted tag </ins> -
          <sup> superscript tag to write a 2 is to the power of 2 </sup> - -- eg
          2<sup>2</sup> -
          <sub>
            subscript tag to write a text below like chemical formula H2O
          </sub>
          - --eg H<sub>2</sub>O - <small> to write a smaller text </small> -
          <mark> to highlight the text</mark>

          <!-- - Strong tag <strong> -->
          - its appear similar to bold but also tells browser that this text have
          importance in document
          <!-- - Emphasis tag <em> -->
          - its visual as italic tag but it gives a deep meaning and importance
          for a browser ## FORM in html ## input tags - these are self closing
          tags - <input type="text" /> will take input as text -
          <input type="number" /> only numbers - <input type="password" /> will be
          hide by \*\*\*\* - <input type="date" /> we can select date -
          <input type="time" /> we can select time - <input type="radio" /> tto
          create a radio button - <input type="checkbox" /> tto create a checkbox
          button - <input type="submit" /> tto create a submit button - Attributes
          for input - Name - <input type="text" name="name" /> its for a server to
          understand - Value - <input type="text" value="default" /> to add a
          default value - Placeholder -
          <input type="text" placeholder="this is a place holder" /> - Max Min
          only for number - <input type="number" max="10" /> set range for a
          number - Readonly - <input type="number" max="10" readonly /> can only
          be read can not change - Hidden -
          <input type="number" max="10" hidden /> it hides the input feild -
          Select (dropdown)
          <select>
            <option>Red</option>
            <option>Blue</option>
          </select>
        </i></b
      >

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
<input type="text" name="username" /> <!-- Helps server understand the field -->
<input type="text" value="Default Value" /> <!-- Default input value -->
<input type="text" placeholder="This is a placeholder" /> <!-- Displays hint text -->
<input type="number" max="10" min="1" /> <!-- Restricts number input range -->
<input type="text" readonly value="Cannot edit this text" /> <!-- Read-only field -->
<input type="hidden" value="secret" /> <!-- Hidden field -->
```

### Dropdown (Select)
```html
<select>
  <option>Red</option>
  <option>Blue</option>
</select>
```

---

This document serves as a quick reference for HTML basics in web development. 🚀

