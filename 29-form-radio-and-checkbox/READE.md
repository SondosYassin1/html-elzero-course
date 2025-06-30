# 🔘 Radio Buttons & Checkboxes in HTML Forms

In this lesson, we cover two essential input types used in forms for selecting options:  
**`radio`** (choose one) and **`checkbox`** (choose multiple).

---

## 🔘 Radio Buttons

Use `radio` inputs when you want the user to **choose only one option** from a list.

<input type="radio" name="os" value="windows"> Windows
<input type="radio" name="os" value="mac"> Mac
<input type="radio" name="os" value="linux"> Linux

All radio buttons that share the same name belong to the same group.

Only one option in that group can be selected at a time.

✅ Better with Labels
It’s best practice to associate each radio input with a <label>:
<input type="radio" id="windows" name="os" value="windows" checked>
<label for="windows">Windows</label>

<input type="radio" id="mac" name="os" value="mac">
<label for="mac">Mac</label>

<input type="radio" id="linux" name="os" value="linux">
<label for="linux">Linux</label>
The id links the input to its label via the for attribute.

Clicking on the label selects the corresponding radio input.

⚠️ Reminder: IDs must be unique on the page.

☑️ Checkboxes
Use checkbox inputs when the user can select more than one option.

<input type="checkbox" id="html" name="skills" value="HTML">
<label for="html">HTML</label>

<input type="checkbox" id="css" name="skills" value="CSS">
<label for="css">CSS</label>

<input type="checkbox" id="js" name="skills" value="JavaScript">
<label for="js">JavaScript</label>
You can check multiple boxes at once.

Useful for questions like: “What are your skills?”, “What services do you offer?”, etc.

🧠 Summary
Input Type Use Case Selects
radio Choose one from a set One option only
checkbox Choose one or more from a set Multiple options

Always use label elements for better accessibility.

Use the checked attribute to pre-select an option.
