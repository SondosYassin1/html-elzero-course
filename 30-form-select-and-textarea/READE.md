🧠 Lesson 30: <select> and <textarea> Elements in HTML
📌 1. The <select> Element
Used to display a dropdown list of options. You can allow the user to select one or multiple options.

✅ Basic Usage:
<label for="book">Choose book</label>
<select name="book" id="book">

  <option value="1">Book 1</option>
  <option value="2">Book 2</option>
  <option value="3">Book 3</option>
  <option value="4">Book 4</option>
</select>
value: This is the data sent to the backend when a user selects an option.

option: Each option inside the dropdown is defined using this tag.

🧩 2. Grouping Options with <optgroup>
When you have a large number of options, you can organize them into categories using <optgroup>:
<select name="book" id="book">

  <optgroup label="Romantic Books">
    <option value="1">Book 1</option>
    <option value="2">Book 2</option>
  </optgroup>
  <optgroup label="Thriller Books">
    <option value="3">Book 3</option>
    <option value="4">Book 4</option>
  </optgroup>
</select>
label: Displays the name of the group to the user.

The <optgroup> itself cannot be selected—it's just for grouping.

🎯 3. Allowing Multiple Selections (multiple)
To let the user select more than one option:
<select name="book" id="book" multiple>

  <option value="1">Book 1</option>
  <option value="2">Book 2</option>
</select>
Hold Ctrl (or Cmd on Mac) while clicking to select multiple options.

🌟 4. Pre-selecting an Option (selected)

<option value="5" selected>Book 5</option>
This makes “Book 5” selected by default when the page loads.

📝 5. The <textarea> Element
Used for entering longer blocks of text. Unlike <input>, it has an opening and closing tag:
<textarea name="message" id="message" cols="30" rows="10"></textarea>
cols: Number of visible character columns (width).

rows: Number of text rows (height).

📚 Quick Tips:

Use <select> when you want to offer a list of predefined choices.

Use <textarea> when you expect longer user input.

Organize complex dropdowns with <optgroup> to improve usability.
