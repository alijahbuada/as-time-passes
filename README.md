# as time passes

An exhibition of fourteen pieces by Alijah Jacob, heard one dark room at a time.

## Put it on GitHub Pages

1. Create a new repository (for example `as-time-passes`) and upload everything in this folder: `index.html`, `rooms.js`, and the `audio` folder.
2. In the repository, open **Settings → Pages**, set the source to the `main` branch, root folder, and save.
3. The page will be live at `https://alijahbuada.github.io/as-time-passes/` after a minute or two.

## Change the wall text

All wall text lives in `rooms.js`.

- `note` at the top is the curatorial note on the entrance.
- Each room has `title`, `release`, `date`, `statement`, and an optional `attribution` for pulled quotes.

## Add or reorder rooms

Rooms play in the order they appear in `rooms.js`. To add one, drop the MP3 in `audio/` and add an entry with its `file`, `duration` (seconds) and one of the installations:
`blinds`, `column`, `hooked`, `static`, `words`, `sunset`, `fog`, `wind`, `constellation`, `rebirth`, `carve`, `shrine`, `sky`, `door`.

`peaks` is the track's loudness shape, used to draw the exit ticket. A new room without it still works; give it a list of 120 numbers between 0 and 1 for a proper waveform.
