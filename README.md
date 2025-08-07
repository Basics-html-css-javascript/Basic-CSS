# 🌐 Complete  CSS Tutorial — Basic to Advanced

Welcome to the **HTML + CSS Tutorial Project**. This guide will take you through the **basics of HTML**, **types of CSS**, and **advanced styling using external CSS**.

---

## 🧱 File 1: `1_basic_html.html`

This file introduces **HTML structure** and common elements:

```html
<!DOCTYPE html>
<html>
<head>
  <title>HTML Basics</title>
</head>
<body>

  <h1>Welcome to HTML</h1>
  <p>This is a paragraph.</p>
  <a href="#">This is a link</a><br>
  <img src="https://via.placeholder.com/150" alt="Sample Image"><br>
  <ul>
    <li>Unordered List Item</li>
  </ul>
  <ol>
    <li>Ordered List Item</li>
  </ol>
  <table border="1">
    <tr><th>Name</th><th>Age</th></tr>
    <tr><td>Alice</td><td>24</td></tr>
  </table>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name"><br>
    <input type="submit" value="Submit">
  </form>

</body>
</html>
```

🎨 File 2: 2_inline_css.html
This file shows inline CSS usage:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Inline CSS Example</title>
</head>
<body>

  <h1 style="color: green; font-size: 30px;">Styled Header</h1>
  <p style="color: gray;">This paragraph is styled using inline CSS.</p>
  <div style="background-color: yellow; padding: 10px;">
    Inline CSS allows you to add styles directly into HTML elements.
  </div>

</body>
</html>
```

🎯 File 3: 3_external_css.html
This file uses external CSS. It includes:

Class selectors

ID selectors

Universal selectors

Element selectors

Group selectors

Box model properties

```html
<!DOCTYPE html>
<html>
<head>
  <title>External CSS Example</title>
  <!-- Linking external CSS file -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <h1 class="main-heading">Styled with External CSS</h1>
  <p class="paragraph">This paragraph is styled using an external CSS file.</p>
  <div id="container">
    <p>Box model example with padding and margin.</p>
  </div>
  <ul>
    <li class="list-item">List Item 1</li>
    <li class="list-item">List Item 2</li>
  </ul>

</body>
</html>

```

🧾 styles.css (External Stylesheet)
```css
/* Universal Selector */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Element Selector */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
}

/* Class Selector */
.main-heading {
  color: navy;
  text-align: center;
  margin: 20px;
}

.paragraph {
  color: darkgreen;
  font-size: 18px;
  padding: 10px;
}

/* ID Selector */
#container {
  border: 2px solid #333;
  padding: 15px;
  margin: 20px;
  background-color: #fff;
}

/* Group Selector */
h1, p {
  margin-bottom: 15px;
}

/* Class for List Items */
.list-item {
  list-style: square;
  margin-left: 20px;
}
```

🖼️ Output
Here is the output preview of the final styled page:


<img width="120" height="325" alt="output" src="https://github.com/user-attachments/assets/210fa8f6-1013-4c98-b97e-a4e6e41d4faa" />
