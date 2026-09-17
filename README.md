# Rianne de Heide academic website

This is the Jekyll source for `https://riannedeheide.github.io`.

## Young academics

The “For young academics” section is organised by career stage and topic. The current substantive page is `phd-netherlands.html`; placeholder pages are already present for advice during the PhD, postdocs, early faculty, parents/caregiving, the Dutch research community, and grants.

## Notes & Exposition

Technical notes live in `_notes/` and are listed newest-first on `notes.html`. PDFs that should remain available from the website are stored in the site root.

## Automatic external-link check

`.github/workflows/check-external-links.yml` runs whenever a commit is pushed to the `main` branch (and can also be run manually from GitHub Actions). It checks HTTP/HTTPS links in the website source. A broken external link makes that GitHub Actions run fail, giving the commit a red check and a report under the repository's **Actions** tab. GitHub can also send a notification for failed Actions according to the account's notification settings. The workflow does not itself stop GitHub Pages from publishing unless repository branch-protection rules are separately configured to require it.
