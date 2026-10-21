# DVD Collection

Searchable catalogue of David Comstock's DVD, Blu-ray and 4K discs: where each one is shelved, plus director, cast, release date, runtime and a source link for each film.

Live site: https://comstocd.github.io/dvd-collection/

- `index.html` — the page
- `collection.js` — the data (`window.COLLECTION.items`): one entry per shelf item, each with location, quantity, format, notes and a `films` list

Film details come from each title's Wikipedia article or the page linked in its `source` field. Entries flagged `check`/`ambiguous` need confirming against the disc.
