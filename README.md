What is HTML?

HTML (HyperText Markup Language) is used to create web pages.
It tells the browser what to display (text, images, links, forms, etc.).

HTML is not a programming language – it is a markup language.

Basic Structure of HTML

Every HTML page follows this structure:

<!DOCTYPE html>
<html>
<head>
    <title>My First Page</title>
</head>
<body>

    <h1>Hello World</h1>
    <p>This is my first HTML page.</p>

</body>
</html>

Explanation:

<!DOCTYPE html> → tells browser this is HTML5

<html> → root tag

<head> → page info (title, CSS, meta)

<title> → title shown on browser tab

<body> → content shown on the page

Common HTML Tags
Headings
<h1>Heading 1</h1>
<h2>Heading 2</h2>

Paragraph
<p>This is a paragraph</p>

Link
<a href="https://google.com">Go to Google</a>

Image
<img src="image.jpg" alt="My Image">

Line Break
<br>

Lists
Ordered List
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>

Unordered List
<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>

Table
<table border="1">
  <tr>
    <th>ID</th>
    <th>Name</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Poornima</td>
  </tr>
</table>

Form Example
<form>
  Name: <input type="text"><br><br>
  Email: <input type="email"><br><br>
  <input type="submit" value="Submit">
</form>
