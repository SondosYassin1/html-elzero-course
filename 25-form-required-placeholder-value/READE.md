✨ Important Attributes for Form Inputs
In this part of the lesson, I learned about some essential attributes that are commonly used with <input> elements inside a form.

1️⃣ required Attribute
This makes the input field mandatory to fill out before submitting the form.
<input type="password" required>
📝 If the user tries to submit the form without filling this field, the browser will automatically show a validation message.

It only checks fields with required.

Optional fields without this attribute will be skipped.

2️⃣ placeholder Attribute
The placeholder adds temporary hint text inside the input field, helping users understand what to enter.
<input type="text" required placeholder="Username">
<input type="password" required placeholder="Write a complex password">
🔹 The placeholder disappears as soon as the user starts typing.
🔹 It’s useful when no <label> is used, or to give extra hints.

3️⃣ value Attribute
This defines a default value inside the input field when the form loads.
<input type="email" value="o@nn.sa">
📌 In this example:

The type="email" ensures the input follows a valid email pattern.

The field will already contain a default email address.

✅ It’s also used with submit buttons to change the button text:
<input type="submit" value="Save">
Instead of showing the default "Submit" text, the button will say "Save".

📌 Use Case
The value attribute is helpful when:

You want to pre-fill the form with existing data.

You're building an edit form to update user information.

