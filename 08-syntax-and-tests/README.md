08 - Syntax and Tests
Syntax refers to the structure and correct way of writing HTML code.

Browsers ignore extra white spaces. So even if you leave many spaces or line breaks between elements, they will not affect how the page is displayed.

If you want to add visible spacing between elements, you’ll need to use CSS.

Attributes and Their Syntax
Some HTML elements can have many attributes — sometimes 8 or more.

The attribute value can be written using single quotes (' '), double quotes (" "), or — in some cases — no quotes at all, if the value is a single word.
<input type=text> <!-- This is valid -->
⚠️ However, if the value contains spaces, you must use quotes. Otherwise, the browser will misunderstand the rest of the words as separate attributes.

<!-- ❌ Wrong -->
<div title=This is wrong>

<!-- ✅ Correct -->
<div title="This is correct">
Using quotes helps the browser understand that the value is just content, not code or multiple attributes. Always prefer using quotes for clarity and to avoid unexpected bugs.
