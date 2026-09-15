# brycepickwell.com — v2

Static site, no build step, no framework, no JS dependencies beyond
plain CSS/HTML. Base64-embedded images, so no separate asset files
to upload.

## Pages
- `index.html` — homepage: name, email, About/Work/Blog nav, dead-centered on the page
- `work.html` — career timeline (colored bars, hover for full bio bullets per role)
- `about.html` — short present-tense bio
- `blog.html` — photo grid (16 photos), hover to enlarge in place; "work in progress" note, no writing yet

## Deploy
Go to the GitHub repo → "Add file" → "Upload files" → drag in all four
.html files (they'll overwrite the existing ones since the names
match) → commit. Vercel will auto-redeploy within a minute or two
since it's already connected to this repo.

## Run locally
python3 -m http.server 8000
then visit http://localhost:8000
