💡 Lesson 24 – Understanding <form> and <input> Elements
In this lesson, I learned how to create a basic HTML form to collect and submit user input.

🧾 Basic Form Elements:
<form>: The main container that holds all form fields.

<input>: Used to collect data from users. It is an inline and self-closing tag.

The most important attribute is type, which defines the input type:
<input type="text">     <!-- For text input -->
<input type="password"> <!-- For password input -->
🏷️ Describing Inputs with <label>
To help users understand what to enter, we use the <label> element to describe each input field:
<label>Username</label>
<input type="text">

✅ Full Example:
<form>
  <div>
    <label>Username</label>
    <input type="text">
  </div>
  
  <div>
    <label>Password</label>
    <input type="password">
  </div>
  
  <input type="submit" value="Login">
</form>
I used <div> to organize each input with its label.

The submit button is created using <input type="submit">.

📌 Quick Notes:
Always use a <label> for each <input> to improve accessibility and clarity.

Make sure to use the correct type for each input.

<form> is essential for login, registration, and any user input forms.

