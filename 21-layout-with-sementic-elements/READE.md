21 - Improving Structure Using Semantic Elements Instead of <div>
🔄 Replacing <div> with Semantic Tags
Instead of wrapping your header with a <div class="header">, use the semantic <header> tag.

Similarly, replace main sections with <main>, <section>, <article>, <aside>, and <footer> where appropriate.

Note:
Replacing <div> with semantic tags does not mean <div> is obsolete.
There are still cases where <div> is needed, especially when no semantic element fits the purpose.

⚙️ Using Classes with Semantic Elements
You can add classes to semantic elements for styling or identification:

<header class="main-header">
  <!-- header content -->
</header>

<section class="features-section">
  <!-- section content -->
</section>

This is helpful when you have multiple headers or sections and need to differentiate them.

🧭 Navigation and Sidebar
Most projects have only one <nav> element for navigation.

Sidebar replaces <div class="sidebar"> with the semantic <aside> element:

<aside class="sidebar">
  <!-- sidebar content -->
</aside>

📰 Articles and Sections
For blog posts or independent pieces of content, use <article>.

Articles can be placed inside <section> if grouped logically.

Example:

<section>
  <article>
    <h2>Article Title</h2>
    <p>Article content here...</p>
  </article>
</section>

📷 Figure and Figcaption
Instead of wrapping an image and its caption in a <div>, HTML5 provides <figure> and <figcaption> to semantically group them.

Before (using <div>):

<div>
  <img src="../game.webp" alt="Game Image">
  <p>Caption of the image</p>
</div>

After (semantic way):

<figure>
  <img src="../game.webp" alt="Game Image">
  <figcaption>Caption of the image</figcaption>
</figure>
Summary
Old Approach	Semantic HTML5 Approach
<div class="header">	<header>
<div class="sidebar">	<aside>
<div> (for articles)	<article>
<div> (image + caption)	<figure> + <figcaption>

Using semantic elements improves:

Accessibility for screen readers

SEO by providing meaningful page structure

Code readability and maintainability
