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

## Image tage

```html
<img src="www.image.com" alt="image" />
<!-- here we are taking directly a image from a url -->
<img src="./images" alt="image" />
<!-- here we are taking image from our local machine -->
```

```

```
