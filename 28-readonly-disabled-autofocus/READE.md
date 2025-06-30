# 🧩 Input Attributes for Better Form Control in HTML

In this lesson, we explore attributes that give more control over user input behavior and form field functionality.

---

## 🔒 `readonly` Attribute

The `readonly` attribute makes an input **read-only** — it cannot be modified by the user, but its value **is submitted** with the form.

<input type="text" value="Osama" readonly>

Users can see the value.

Cannot change it.

Still gets sent to the server when the form is submitted.

Great for preserving important information without allowing edits.

🚫 disabled Attribute
The disabled attribute disables an input completely:

<input type="email" value="example@mail.com" disabled>
Input is not editable.

It is not submitted with the form.

Useful when you want to display a value but prevent interaction — e.g., email during payment.

🎯 autofocus Attribute
The autofocus attribute sets focus automatically to the specified input field when the page loads.

<input type="text" name="subject" autofocus>
Makes it easier for users to start typing right away.

Only one element in a document can have autofocus.

🔐 minlength and maxlength
These attributes define the minimum and maximum number of characters allowed in input fields like passwords or usernames.

<input type="password" minlength="10" maxlength="20">
Prevents submitting the form unless the input matches the character limits.

Works with input types like text, password, email, etc.

✅ Summary
Attribute Description
readonly Makes input non-editable but still sends the value to server

disabled Disables input entirely; it’s not editable and not submitted

autofocus Automatically focuses the input when the page loads
minlength Sets the minimum number of characters required for input

maxlength Sets the maximum number of characters allowed in the input

These attributes enhance form behavior, guide users, and help with validation.
