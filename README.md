# Group 4 — Member Directory

A single-page member directory for **Group 4**, Grade 11, Immaculate Conception
Polytechnic — San Jose Del Monte, Bulacan.

The page has a searchable roster table of all seven members, followed by a full
profile for each one: bio, skills, and educational background.

## Running it

No build step, no dependencies. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publishing with GitHub Pages

Push this folder as the repository root, then in the repo go to
**Settings → Pages → Build and deployment**, set *Source* to **Deploy from a
branch**, pick branch `main` and folder `/ (root)`, and save. The site appears at
`https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Files

```
index.html    the whole page — HTML, CSS and the roster filter script
img/          member photos, cropped square and compressed for the web
```

## A note on what is not published here

This page is on the public web, and most of the members are minors. Personal
mobile numbers, email addresses, complete home addresses, and birthdates are
deliberately **left out** — only first-level location (San Jose Del Monte,
Bulacan) and age are shown.

Please keep it that way. Anything committed to this repository stays in the git
history permanently, so removing a detail in a later commit does not make it
private again.
