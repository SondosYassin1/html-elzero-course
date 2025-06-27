18 - HTML Entities
Sometimes, you need to display HTML code as plain text instead of having the browser interpret it as actual HTML.

For example:

<div>This is my <p> div</div>

❌ This will break your layout, because the browser tries to render <p> as a real element, causing invalid structure.

✅ The Solution: HTML Entities
To print special characters (like <, >, &, etc.) as text, use their HTML entity codes.

🔤 Most Common Entities:
Character Entity Code Output
< &lt; <

>     &gt;	>
>
> & &amp; &
> " &quot; "
> ' &apos; '

So instead of:

<div>This is my <p> div</div>

✅ Write:

<div>This is my &lt;p&gt; div</div>

Now it will be shown correctly on the page:
This is my <p> div

➕ More Useful Entities:
Symbol Entity Output
≈ &asymp; ≈
© &copy; ©
℗ &copysr; ℗
√ &radic; √

You can find many more by searching for:
🔍 "HTML Entities List" on Google or visit https://dev.w3.org/html5/html-author/charref

HTML entities are super useful when:

You want to show code on your website

You're building educational content

You're protecting your layout from breaking due to unescaped tags
