# ♿ Understanding ARIA and Accessibility in Rich Applications

## 🔤 What is ARIA?

**ARIA** stands for **Accessible Rich Internet Applications**.  
It is a set of attributes that define ways to make web content and web applications more accessible to people with disabilities, especially those using screen readers.

---

## 🛠️ Why Use ARIA?

In dynamic applications (e.g., when using JavaScript to create interactive UI elements), screen readers may not understand non-semantic HTML.  
ARIA attributes help fill in the missing accessibility information.

For example, when creating checkbox-like UI using `<div>` elements, we must add ARIA attributes to make them recognizable and usable by assistive technologies.

---

## 🧪 Example

<!-- Basic Checkbox-like Div with ARIA -->
<div id="plan1"
     role="checkbox"
     aria-checked="true"
     tabindex="0"
     aria-labelledby="label1">
    Plan One
</div>
<label id="label1" for="plan1">Plan One label</label>

🔍 Explanation:
role="checkbox": Tells the screen reader that this div acts as a checkbox.

aria-checked="true": Marks it as selected.

tabindex="0": Allows the user to tab through the element using keyboard.

aria-labelledby="label1": Links the div to a label that describes it.

🧪 Example Without ARIA:

<div>Plan One</div>
<div>Plan Two</div>
<div>Plan Three</div>
➡️ This version is not accessible. Screen readers won’t know what these elements are supposed to be.

🌟 Tools Like Lighthouse
Tools like Lighthouse help you audit accessibility, including use of ARIA, labels, contrast, focus management, and more.

✅ Summary
ARIA attributes help bridge the gap between custom HTML elements and accessibility standards.
They are essential when building rich, dynamic web interfaces — ensuring your application is usable by everyone.

Keep accessibility in mind; it’s not optional — it’s part of building a better web. 🌍💙
