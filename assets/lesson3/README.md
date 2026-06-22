# Lesson 3 extension thumbnails

Drop the two watch-card images here, with these exact filenames:

- `grayson-perry.jpg` — the Channel 4 "Grayson Perry Has Seen the Future" still.
- `deepmind-channel.jpg` — the Wyclef Jean / YouTube × Google DeepMind music-demo still.

Any common web format works if you keep the name+extension consistent with the
`<img src="...">` in `index.html` (search for `assets/lesson3/`). Recommended:
landscape ~480×270 (16:9), JPG or WebP, kept reasonably small (<200 KB).

The third card ("The Thinking Game") already uses the official YouTube thumbnail,
so it doesn't need a file here.

Until these files are added, the cards fall back to a coloured gradient + play badge
(the `onerror` handler removes the broken image), so nothing looks broken.
