# ♿ Web Accessibility (a11y) – Key Concepts & Best Practices

## 📘 What is Accessibility?

**Accessibility (a11y)** refers to designing and developing websites so that **everyone**, including people with disabilities (e.g. visual impairments), can use them.

For example, blind users often rely on **screen readers** to navigate websites.  
To support them, developers must follow accessibility rules and use semantic, meaningful HTML.

---

## ✅ Use the Right HTML Element

Using the correct element is key for accessibility.  
For instance:

```html
<!-- ❌ Not Accessible -->
<div>Send</div>

<!-- ✅ Accessible -->
<button>Send</button>

The first example might be styled and made clickable using JavaScript, but a
<div>
  has no semantic meaning, and screen readers won’t recognize it as a button.
  Using
  <button>
    is correct — it’s natively focusable, clickable, and announced properly by
    assistive tools. 🔍 How to Check for Accessibility Issues 1. Use Live Server
    (not File Protocol) Open your webpage via http:// instead of file:// This is
    necessary for accessibility tools like Lighthouse to work correctly. 2. Open
    Lighthouse (in Chrome DevTools) Go to DevTools > Lighthouse Choose the
    Accessibility category Run an audit It will generate a report with specific
    accessibility issues found in your page. 🧪 Common Issues Found When testing
    a basic form, Lighthouse pointed out: ❌ The
    <html>
      tag was missing the lang attribute ✅ Fix:
      <html lang="en">
        ❌ Input fields were missing
        <label>
          elements ✅ Fix:
          <label for="email">Email:</label>
          <input id="email" type="email" />
          ❌ No spacing between inputs and buttons (poor layout/readability) ✅
          Fix: Add line breaks or proper spacing:
          <input type="text" /><br />
          <button>Submit</button>
          💡 Summary Accessibility makes your site usable for everyone. Use
          semantic HTML (<button>
            ,
            <label
              >,
              <nav>
                , etc.) Always test your site with Lighthouse or accessibility
                checkers. Build with empathy — not everyone uses the web the
                same way. Accessibility isn’t extra — it’s essential. 🌍💙
              </nav></label
            >
          </button></label
        >
      </html>
    </html>
  </button>
</div>
```
