19 - Semantic Elements in HTML5
In the past, web layouts were mostly built using multiple <div> elements nested inside each other — like this:

<div>
  <div>
    <div>Content</div>
  </div>
</div>

😕 This approach made the structure unclear and unsemantic — browsers and developers had no idea what each section was for.

✅ HTML5 to the Rescue
HTML5 introduced semantic elements — elements with descriptive names that help both browsers and developers understand the purpose of the content.

🧱 Common Semantic Elements
Element Purpose

<header>	Top section of the page or section (often contains logo or intro)
<nav>	Navigation bar (links to other pages or sections)
<main>	Main content of the page
<section>	A logical group of related content
<article>	A self-contained piece of content (blog post, news item, etc.)
<aside>	Sidebar (related content like ads, menus, or tips)
<footer>	Bottom of the page (contains copyright, contact info, etc.)

🧩 Example Structure

<body>
  <header>This is the header</header>

  <nav>
    <a href="#">Link 1</a> |
    <a href="#">Link 2</a> |
    <a href="#">Link 3</a>
  </nav>

  <main>
    <section>
      <article>
        <h2>Article Title</h2>
        <p>Some article content...</p>
      </article>
    </section>

    <aside>
      <p>This is a sidebar</p>
    </aside>

  </main>

  <footer>© 2025 Your Site</footer>
</body>

🔍 Why Use Semantic Elements?
✅ More accessible to screen readers

✅ Improves SEO

✅ Easier to read and maintain

✅ Adds meaning to your layout (not just styling)

Think of them as <div>s — but with purpose and meaningful names.
