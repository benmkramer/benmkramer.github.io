Personal site (retro edition)
=============================

Files
-----
- `index.html`: 90s-inspired homepage with About, Pets, Links, Guestbook.
- `styles.css`: maximalist theme styles (tables, marquees, sparkle trail).

Customize
---------
- About: Your intro is in the `#about` section.
- Pets: Place images in `images/` and use these filenames:
  - `images/dog.jpg`
  - `images/cat-1.jpg`
  - `images/cat-2.jpg`
  Update alt text and captions as you like.
- Links: GitHub and LinkedIn live in the `#links` section.
- Meta: Page `<title>` and description live in the `<head>`.

Local preview
-------------
Open `index.html` in a browser, or run a simple server:

Python 3:
  python3 -m http.server 8080
Then visit http://localhost:8080

GitHub Pages
------------
For `username.github.io` repos, Pages serves from the default branch root by default. Commit and push:

  git add .
  git commit -m "Add simple personal site"
  git push origin main

Optional ideas
--------------
- Add `images/profile.jpg` to improve link previews (OG image).
- Add pet names and more photos (add more rows in the Pets table).
- Bring back a modern layout in a new branch if you want a calmer vibe.
