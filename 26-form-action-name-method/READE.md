# 📝 Advanced Form Attributes and Data Submission

In this lesson, we will learn about some advanced attributes in HTML forms that help you send data to the backend server.

---

## 🔗 The `action` Attribute

The `action` attribute specifies the URL (endpoint) where the form data will be sent for processing.

```html
<form action="sondos.php" method="GET">
  <!-- form inputs -->
</form>

When the user submits the form, the data will be sent to sondos.php. If action
is empty or omitted, the form submits data to the same page it is on. 🆔 The
name Attribute on Inputs Each input field must have a name attribute. This name
acts as the key for the data sent to the server. html Copy code
<input type="text" name="user" />
When the form is submitted, the data sent will be in the format:
user=the_input_value 🌐 Data Transmission Methods: GET vs POST GET Method Data
is appended to the URL as query strings. Example:
https://example.com/sondos.php?user=abc&age=25 Data is visible in the browser
URL. Useful for non-sensitive data or searches. POST Method Data is sent in the
request body, not visible in the URL. More secure for sensitive information.
Example: Form data won't appear in the URL but can be inspected in developer
tools under Network tab. 🛠️ How to Check Sent Data Use browser Developer Tools →
Network tab Submit the form and inspect the request payload or URL parameters.
This helps verify what data is actually sent to the server. ✅ Summary Use the
action attribute to set the destination URL of form data. Always set meaningful
name attributes on inputs. Choose the right method (GET or POST) based on your
data privacy needs. Use browser dev tools to inspect submitted data.
```
