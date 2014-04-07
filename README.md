bbplayer
============

A Modern, Minimalist HTML5 Audio Player

[![bbplayer](https://lh3.ggpht.com/-tC8Zj6Bpg04/UcMquJhtiLI/AAAAAAAABgI/cXg6RtQrgMc/s1600/bbplayer.png)](http://darrenderidder.github.com/bbplayer)

About
-----

bbplayer is a minimalist HTML5 Audio player. With bbplayer you can:
  * make a playlist of tracks
  * design your own buttons or use the ones included
  * put several bbplayers on a page that play one at a time
  * support all browsers with MP3 and OGG formats

bbplayer uses CSS classes. Start with a *bbplayer* class containing controls
like *bb-rewind*, *bb-play*, *bb-forward*, etc. and the HTML5 *audio* element;
bbplayer.js takes care of the rest.

```html
<link rel="stylesheet" href="css/bbplayer.css">
```

```html
<div class="bbplayer">
  <span class="bb-rewind"></span>
  <span class="bb-play"></span>
  <span class="bb-forward"></span>
  <span class="bb-trackTime"></span>
  <span class="bb-trackLength"></span>
  <span class="bb-trackTitle"></span>
  <audio>
    <source src="media/x.mp3"/>
    <source src="media/x.ogg"/>
    <source src="media/y.mp3"/>
    <source src="media/y.ogg"/>
  </audio>
</div>
```
    
Then include **bbplayer.js**:

```html
<script src="js/bbplayer.js"></script>
```

See **bbplayer.html** or visit http://darrenderidder.github.com/bbplayer for an example.

FAQ
---

_Why is it called bbplayer?_

I made it for my piano teacher's web site, brianbrowne.com.

_Does it have Flash fallback?_

Nope.

_How do I stop looping?_

Change js/bbplayer.js to use `var repeat=false;`