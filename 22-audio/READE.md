# 🔊 The `<audio>` Tag in HTML

The `<audio>` element allows you to embed audio files on your web page.  
There are two main ways to use it: with a `src` attribute, or with `<source>` tags inside the element.

---

## ✅ Syntax 1: Single Source

<audio src="audio.mp3" controls></audio>

This works when you're using one file format only.

✅ Syntax 2: Multiple Sources (Recommended)
<audio controls>

  <source src="audio.wav" type="audio/x-wav">
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
Why use multiple <source> tags?
Different browsers support different formats.

The browser will choose the first compatible format.

This improves cross-browser compatibility.

🎵 MP3 (audio/mpeg) is widely supported by modern browsers. If you're only targeting modern browsers, you can use just .mp3.

🎯 MIME Types for Audio
Each audio file format has a MIME type used in the type attribute:

File Extension MIME Type
.mp3 audio/mpeg
.wav audio/x-wav
.ogg audio/ogg

Example:

<source src="sound.wav" type="audio/x-wav">
<source src="sound.mp3" type="audio/mpeg">
🛠️ Common Audio Attributes
<audio controls autoplay loop muted>
  <source src="sound.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
Attribute	Description
controls	Displays play, pause, volume, and seek options
autoplay	Starts playback automatically when the page loads (might be blocked by some browsers unless muted)
loop	Repeats the audio automatically when it ends
muted	Mutes the audio on load (useful for autoplay)

⚠️ Note: Autoplay is blocked by most browsers unless the audio is muted.

📌 Fallback Message
If the browser does not support the audio element, you can display a message:
<audio controls>

  <source src="sound.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>

✅ Summary
Use <audio> to embed sound/music in your webpage.

Add multiple <source> elements for better compatibility.

Use attributes like controls, loop, and autoplay to improve user experience.

Always provide a fallback message for unsupported browsers.
