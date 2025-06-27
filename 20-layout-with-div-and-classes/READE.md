20 - Layout With Div And Classes
Today, we will build the basic structure of a website (e.g., Amazon) using only HTML, with <div> containers and classes for organization.

🏗️ Structure Breakdown

1. Header Section
   Wrap the header area inside a <div> with class header.

Add a logo as an <h2> element.

The main navigation links are grouped inside an unordered list <ul> because there are many links and they don’t have a specific order.

<div class="header">
  <h2>Logo</h2>
  <ul>
    <li>Home</li>
    <li>About</li>
    <li>Services</li>
    <li>Contact Us</li>
  </ul>
</div>
2. Navigation Bar
Use another <div> with class navigation to hold secondary or additional links.

Inside it, again use an unordered list <ul> for the links.

<div class="navigation">
  <ul>
    <li>Link 1</li>
    <li>Link 2</li>
    <li>Link 3</li>
    <li>Link 4</li>
  </ul>
</div>
Note:
Sometimes, you can use <ul> directly without wrapping it in a <div>, especially if it’s standalone to avoid unnecessary markup.

3. Main Content Area
   Create a <div> with class content to contain the main page content.

<div class="content">
  Content goes here...
</div>
4. Sidebar
A sidebar usually appears on the right (in left-to-right languages).

It can contain categories, images, latest members, or other supplementary info.

Wrap it in a <div> with class sidebar.

<div class="sidebar">
  Sidebar content here...
</div>
5. Footer
Footer content goes at the bottom.

Wrap it in a <div> with class footer.

<div class="footer">
  Footer information here...
</div>
🧩 Final Example
html
Copy code
<div class="header">
  <h2>Logo</h2>
  <ul>
    <li>Home</li>
    <li>About</li>
    <li>Services</li>
    <li>Contact Us</li>
  </ul>
</div>

<div class="navigation">
  <ul>
    <li>Link 1</li>
    <li>Link 2</li>
    <li>Link 3</li>
    <li>Link 4</li>
  </ul>
</div>

<div class="content">
  Main content goes here...
</div>

<div class="sidebar">
  Sidebar content goes here...
</div>

<div class="footer">
  Footer content goes here...
</div>

This simple layout uses semantic class names and <div> elements to organize page sections clearly, making it easier to style and maintain later with CSS.
