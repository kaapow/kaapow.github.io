---
layout: post
microblog: true
audio: 
photo: https://www.kaa.bz/uploads/2018/645cc14611.jpg
date: 2018-05-28 17:46:34 +0400
guid: http://kaa.micro.blog/2018/05/28/does-anyone-know.html
---
Does anyone know how to show the **real** return symbol on iOS? It currently outputs this monstrosity instead. I’m sure [@gruber](https://micro.blog/gruber) had written about this a while ago but I can’t seem to find it.

<img src="https://www.kaa.bz/uploads/2018/645cc14611.jpg" width="600" height="600" />

**Updated:**  
I researched a little bit harder and found this [thread](https://stackoverflow.com/questions/32915485/how-to-prevent-unicode-characters-from-rendering-as-emoji-in-html-from-javascrip). Basically you have to append a unicode variation selector after the html character. This forces the previous character to be rendered as text rather than as an Emoji Symbol.
