14 - Lists in HTML
Lists are among the most commonly used elements in web design.
HTML provides three types of lists, each used for different purposes:

1️⃣ Unordered List (<ul>)
An unordered list displays items with bullet points.

<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ul>
The list is created using the <ul> tag.

Each item is wrapped in a <li> (list item) tag.

Browsers (user agent stylesheets) apply default styling such as bullets and indentation.

✅ You can also nest lists:

<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS
    <ul>
      <li>Angular</li>
      <li>React</li>
      <li>Vue</li>
    </ul>
  </li>
</ul>
2️⃣ Ordered List (<ol>)
An ordered list shows items in a numbered (or lettered) sequence.

<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS
    <ol>
      <li>Angular</li>
      <li>React</li>
      <li>Vue</li>
    </ol>
  </li>
</ol>
➕ Attributes for <ol>:
reversed: Reverses the numbering order.

<ol reversed>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ol>
start: Sets the starting number of the list.

<ol start="100">
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ol>
value: Used on individual <li> elements to set a custom value.

<ol>
  <li value="50">HTML</li>
  <li>CSS</li>
</ol>
type: Sets the type of marker (e.g. numbers, letters, Roman numerals).

<ol type="A"> <!-- A, B, C -->
<ol type="a"> <!-- a, b, c -->
<ol type="I"> <!-- I, II, III -->
3️⃣ Description List (<dl>)
A description list is used to display terms and their descriptions.

<dl>
  <dt>HTML</dt>
  <dd>Language of the web</dd>
  <dd>The first layer of web content</dd>

  <dt>CSS</dt>
  <dd>Language for styling web pages</dd>
</dl>
<dl>: Description list container

<dt>: Description term

<dd>: Description detail

Each list type serves a specific purpose and adds semantic meaning to your content — improving both structure and accessibility.
