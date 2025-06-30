# 🎥 The `<video>` Tag in HTML

The `<video>` element is used to embed video content in a webpage.  
It shares many similarities with the `<audio>` element, including attributes and structure.

---

## ✅ Basic Syntax

<video src="video.mp4"></video>
This is used when you have a single video source.

🔁 Multiple Sources (Fallbacks)
To support various browser formats:

html
Copy
Edit
<video>

  <source src="video.mp4" type="video/mp4">
  <source src="video.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
📌 Note: Most modern browsers support .mp4 — if you're using it, additional formats are optional.

🛠️ Common Video Attributes
html
Copy
Edit
<video
  controls
  autoplay
  loop
  muted
  width="600"
  height="400"
  poster="thumbnail.jpg">

  <source src="video.mp4" type="video/mp4">
  <source src="video.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
Attribute	Description
controls	Displays video player controls (play, pause, volume, etc.)
autoplay	Starts playing the video automatically
loop	Repeats the video continuously
muted	Mutes the video on load (required for autoplay on some browsers)
poster	Shows an image before the video loads or plays
width, height	Sets the size of the video player

💬 Subtitles with <track>
Use the <track> element to provide subtitles, captions, or other timed text tracks:

html
Copy
Edit
<video controls>

  <source src="video.mp4" type="video/mp4">
  <track src="my-file.vtt" kind="subtitles" srclang="en" label="English">
</video>
🔍 Track Attributes:
Attribute	Description
src	Path to the .vtt file
kind	Type of text track (e.g., subtitles, captions, descriptions, metadata)
srclang	Language of the subtitles (e.g., en, fr)
label	Label shown to the user for subtitle selection

📚 Bonus: preload Attribute
You might also encounter the preload attribute:

html
Copy
Edit
<video preload="auto"></video>
It suggests to the browser how much of the video should be loaded in advance:

none: Do not preload

metadata: Load only metadata (duration, dimensions, etc.)

auto: Let the browser decide

👉 It’s not widely needed, but worth reading about to optimize loading performance.

✅ Summary
Use <video> for embedding media-rich content.

Combine multiple <source> elements for broader browser support.

Add accessibility with <track> for subtitles.

Use controls, autoplay, loop, and poster to enhance user experience.
