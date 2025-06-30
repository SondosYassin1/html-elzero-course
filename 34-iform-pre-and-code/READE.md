🧾 HTML Tags: <code>, <pre>, and <iframe>

💻 1. <code> — Code Snippet
Used to display inline computer code.

<p>Use the <code>&lt;h1&gt;</code> tag for main headings.</p>
✅ It's inline, so it appears inside text like any normal word.

Does not preserve spacing or line breaks by itself.

🧱 2. <pre> — Preformatted Text
Preserves spaces, tabs, and line breaks exactly as written inside the tag.

<pre>
This is
  preformatted
      text with
  spacing
</pre>

✅ It's a block-level element.

Commonly used with <code> for displaying code blocks clearly.

💡 Tip:
You can combine <pre> with <code>:

<pre><code>
function hello() {
    console.log("Hello, world!");
}
</code></pre>

🌐 3. <iframe> — Inline Frame
Allows you to embed another webpage, file, or URL within your current page.

<iframe src="page.html" frameborder="0"></iframe>
✅ Used to display:

Another page from your own site

An external URL

A PDF, video, or tool

frameborder="0" removes the border.

You can also control size with width and height.

⚠️ Note:
Some websites block iframe embedding for security using headers like:
X-Frame-Options: DENY or SAMEORIGIN
🔍 Summary Table:
Tag Purpose Notes
<code> Inline code snippets Does not preserve spacing

<pre>	Preformatted block of text	Preserves spacing & line breaks
<iframe>	Embed a web page or file into the page	May be blocked by some sites
