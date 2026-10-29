# Krowsingre Publishing

The website at https://krowsingre.github.io, published by GitHub Pages from this repository.

Each app has its own folder, with its privacy policy inside:

- The Bound Vigil: `the-bound-vigil/privacy/` (https://krowsingre.github.io/the-bound-vigil/privacy/)

A new app gets a folder of its own the same way, and a line on the front page (`index.html`).

## Suggested reading in The Bound Vigil

`the-bound-vigil/suggested.json` is the list TBV shows first in Sanctum's Suggested reading, on every copy, without an app update. Add a book to `books` like this:

```json
{
  "title": "The Book's Title",
  "authors": ["Author Name"],
  "cover": "covers/the-books-title.jpg",
  "about": "A sentence or two about it.",
  "download": "https://example.com/the-book.epub",
  "pinned": true
}
```

Use `download` for a free EPUB, or `buy` with the store's page instead. `cover` can be a full address or a picture in this folder. `pinned` puts a book first. TBV looks the list up once a day.
