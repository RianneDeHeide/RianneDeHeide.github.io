# Rianne de Heide academic website

This repository contains the Jekyll source for https://riannedeheide.github.io.
GitHub Pages uses `_config.yml`; site navigation is in `_includes/navigation.html`.

## Editing

- Homepage: `index.html`.
- Contact instructions and email reveal: `contact.html`.
- Prospective students and postdocs: `students.html`.
- News items (also used on the homepage): `_data/news.yml`.
- Style: `assets/style.css`.
- Paper and note metadata: `_data/`, `_papers/`, `_notes/`.

The email address on the contact page is assembled client-side when the visitor clicks the button. This provides modest resistance to simple scraping, not guaranteed protection from spam or sophisticated crawlers.

Keep the linked PDF files, images, and the `_includes` / `_layouts` folders when updating the site. Repository cleanup guidance is distributed separately from the website files.
