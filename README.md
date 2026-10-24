# Songbattle

Songbattle is a small website to sort the songs of an album (or an artist's whole catalogue) by your personal taste.
In every battle you pick the song you like better; at the end you get your own ranking.

Live: <https://songbattle.app>

## How it works

- Each album has its own page with a `tracklist` array and a small CSS file for the colors.
- `songbattle.js` / `songbattle2.js` run the sorting (merge sort based, one battle per comparison).
- The site is plain HTML, CSS and JavaScript (Bootstrap), no build step needed.

## Add a new album

1. Copy an existing album page and its CSS, e.g. `giant_rooks/HHYB.html` and `giant_rooks/HHYB.css`.
2. Replace the title and the `tracklist` in the HTML and pick an accent color in the CSS.
3. Link the new page in `index.html`.

Or just [open an issue](https://github.com/T0biii/Songbattle/issues/new/choose) with the artist, album and a link.

## Credits

Inspired by [jesseepinkman](https://jesseepinkman.tumblr.com/). Favicon: Musical Note from [twemoji](https://twemoji.twitter.com/).
