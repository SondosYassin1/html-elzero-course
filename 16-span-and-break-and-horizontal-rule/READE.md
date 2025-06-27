16 - Inline & Line-Break Elements (<span>, <br>, <hr>)
🔹 <span> – Inline Container
<span> is a very basic inline element.

It has no default styling from the browser (user agent).

It behaves like regular text — visually nothing changes unless you apply CSS.

✅ Its main purpose is to select or style specific parts of text inside a larger block.

<p>This is a <span class="highlight">very important</span> word.</p>
Use case: Styling or applying JavaScript/CSS to a specific word without affecting the rest of the content.

🔸 <br> – Line Break
The <br> tag is used to create a new line (line break).

It does not create a new paragraph, just forces the content to move to the next line.

<p>Line 1<br>Line 2</p>
<br> is an inline element and self-closing.

🔸 <hr> – Horizontal Rule
The <hr> tag inserts a horizontal line.

It is a block-level element.

Browsers apply default styling, like a gray line with some margin.

<p>Section One</p>
<hr>
<p>Section Two</p>
✅ Use <hr> to visually separate content (e.g., sections or topics).

These elements help you control content flow and apply targeted styles or breaks inside your layout without needing CSS for everything.
