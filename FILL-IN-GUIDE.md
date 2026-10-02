# Site updates

This site is updated without hand-editing HTML: send the new information
(a new studio log, a new project, a new publication, a new research question,
a new DOI — a link and a sentence or two in plain words), and the pages are
regenerated and re-zipped. Extract the new zip over the repo, commit, push.

## What each page draws from

- `index.html` — teasers of the newest studio logs (mirrors `studio-logs.html`).
- `projects.html` — one card per organization repository (name, link, one line).
- `studio-logs.html` — newest-first entries (date, title, one-two sentences, link).
- `research.html` — research questions (number, one line, link to the RQ file).
- `publications.html` — releases with DOI links (title, version, one line, DOI).
- `about.html` — the operator bio and links (rarely changes).

## Images

- `images/the-historiotheque-building.jpg` — the header image (already in place
  once added). Additional images go in `images/` and are referenced by filename.
