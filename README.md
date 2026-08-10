# lucidité — books

The books/reading-log section of **lucidité**, Varun Agarwal's personal
blog — migrated off Cargo, no build step, plain HTML/CSS/JS.

Deploys to **books.varunagarwal.com** via GitHub Pages.

**lucidité** will eventually be the home for the rest of the blog too
(about, photos, and the other sections listed in
`../_cargo-backup/site-nav.md`), added sequentially. This repo is just
the books section for now — a standalone placeholder, not the full site
shell.

## Structure

- `index.html` — the whole page (markup, styles, and the book data all
  live in this one file — see the comment block at the top of it for
  how to add a book)
- `CNAME` — tells GitHub Pages to serve this repo on
  books.varunagarwal.com instead of the default github.io URL

## Related

- `../wander/field-notes` — a separate, already-deployed site
  (wander.varunagarwal.com), same DIY convention
- `../_cargo-backup/site-nav.md` — the old Cargo site's global nav,
  kept for when the full lucidité shell gets built
