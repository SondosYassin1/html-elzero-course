# 🛠️ Advanced Input Types in HTML Forms

In this lesson, we explore some useful and less commonly used input types that enhance user interaction and data handling in forms.

---

## 🔒 Hidden Input: `<input type="hidden">`

- Hidden inputs **do not appear on the webpage**, but their data is sent when the form is submitted.
- Useful for storing things like IDs, tokens, or other data you don’t want visible to users.
- **Note:** Hidden inputs are not for security; users can still see them using browser developer tools.

<input type="hidden" name="user_id" value="12345">

🔄 Reset Button: <input type="reset">
Clears all user-entered data in the form, resetting inputs to their default values.

Useful for allowing users to start over without manually deleting each input.

<input type="reset" value="Reset">

🎨 Color Picker: <input type="color">
Opens a color selection panel where users can pick a color.

The selected color value is submitted as a hexadecimal color code (#RRGGBB).

<input type="color" name="favoriteColor">

📊 Range Slider: <input type="range">
Lets users select a value from a range by sliding a handle.

Supports min, max, and step attributes to control allowed values.

<input type="range" name="volume" min="0" max="100" step="20" value="0">
Attributes:

min: minimum value (e.g., 0)

max: maximum value (e.g., 100)

step: interval between selectable values (e.g., 20)

value: initial value (e.g., 0)

🔢 Number Input: <input type="number">
Allows users to enter a number only.

Enforces numeric input; text input is prevented.

Supports min, max, step, and value attributes.

<input type="number" name="quantity" min="0" max="100" step="10" value="20">

✅ Summary
Use hidden inputs to send data behind the scenes.

Add reset buttons for user convenience.

Use color pickers for easy color selection.

Use range sliders for selecting numeric values within limits.

Use number inputs to restrict input to numbers only.
