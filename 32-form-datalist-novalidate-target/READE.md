🧪 HTML Form Testing: novalidate, target, and datalist
🔧 1. Skipping Validation During Testing with novalidate
When testing a form that includes many input fields and validations, you might want to skip filling out all required fields every time.

Using the novalidate attribute disables form validation:

<form action="" method="post" novalidate>
    <!-- Input fields here -->
</form>
✅ Purpose:

Helps you test how the backend or browser behaves without triggering client-side validation.

Speeds up the development/testing process.

🆕 2. Opening Form Submission in a New Tab with target="\_blank"
Adding target="\_blank" to a <form> makes the submitted data open in a new browser tab:

<form action="" method="post" novalidate target="_blank">
    <!-- Input fields -->
</form>
✅ Useful for testing:

See submitted data separately without losing your current tab.

Great for debugging responses without refreshing the current page.

📋 3. Auto-Complete Searchable Options with <datalist>
The <datalist> element provides an autocomplete dropdown for input fields.
Unlike <select>, users can search and type freely, not just choose from a fixed list.

🔹 Example:
<input list="programming" name="prog">

<datalist id="programming">
    <option value="Python">
    <option value="C#">
    <option value="PHP">
</datalist>
📝 Notes:

You only need the value attribute inside <option>. No closing tag is required.

The list attribute in <input> must match the id of the <datalist> to connect them.

🆚 Difference Between <datalist> and <select>:
Feature <select> <datalist>
Fixed options ✅ Yes ✅ Yes
Free text input ❌ No ✅ Yes
Searchable ❌ No ✅ Yes
Use case Choose only from options Choose or type freely

📌 Summary:

Use novalidate during testing to skip form validation.

Use target="\_blank" to test submissions in a new tab.

Use <datalist> for flexible, searchable input suggestions.
