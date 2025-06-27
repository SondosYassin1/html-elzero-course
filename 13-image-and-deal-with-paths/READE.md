13 - The Image Element (<img>)
The <img> tag is used to display images on a webpage.
It is a self-closing element, meaning it doesn’t need a closing tag.
<img src="image.jpg" alt="Description">

🔑 Main Attributes
Attribute Description
src Source of the image – either from the internet or local files
alt Alternative text – describes the image in case it doesn’t load or for screen readers (important for accessibility & SEO)

🌐 Image Source Examples
From the web:
<img src="https://example.com/profile.jpg" alt="Profile Picture">

From a local folder:
<img src="code.png" alt="Code Screenshot">

From a parent folder (going one level up):
<img src="../code.png" alt="Code Image from Parent Folder">

Use ../ to go up one folder in the directory.
For example: If your image is outside the current folder.

❌ What Happens if the Image is Missing?
If the file name is wrong or the image doesn’t exist:

You'll see an error icon where the image should be.

In Inspect → Console, the browser will show an error like “404 - file not found”.

The alt text will appear in place of the image.

Example:
<img src="missing-image.png" alt="Logo Testing">

📏 Width and Height
You can use the width and height attributes in HTML like this:
<img src="image.jpg" alt="..." width="100px" height="100px">

But it's not recommended to style images directly in HTML.
✅ Use CSS instead for better control and cleaner code.
img {
width: 100px;
height: 100px;
}
Using alt text is especially important for accessibility, SEO, and for users with slow internet or visual impairments.
