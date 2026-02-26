# Music

Place your MP3 or OGG audio files here, then add them to the `PLAYLIST` array in `docs/index.html`.

## Adding Songs

1. Copy your MP3 file into this folder (e.g. `my-track.mp3`)
2. Open `docs/index.html` and find the `PLAYLIST` array near the top of the `<script>` block
3. Add an entry:

```js
const PLAYLIST = [
  { title: "My Track",  artist: "Artist Name",  file: "music/my-track.mp3" },
  { title: "Track Two", artist: "Artist Name",  file: "music/track-two.mp3" },
];
```

The player supports autoplay (with browser permission prompt fallback), prev/next, progress seek, and volume control.
