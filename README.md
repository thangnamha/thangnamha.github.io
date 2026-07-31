# thang-ha-site

A plain HTML/CSS personal academic site — no build step, no frameworks.

## Files
- `index.html` — homepage / bio
- `research.html` — dissertation projects & working papers
- `teaching.html` — courses (placeholder entries, edit with your real ones)
- `cv.html` — embeds `assets/cv.pdf`
- `contact.html` — contact details
- `style.css` — all styling, in one place
- `assets/` — put your photo and CV PDF here

## To personalize
1. Add your photo as `assets/headshot.jpg` (any name works, just update the `src` in `index.html`).
2. Add your CV as `assets/cv.pdf` (keep this exact filename, or update `cv.html`).
3. Edit the bio text directly in `index.html`, and the entries in `research.html` / `teaching.html`.
4. Edit contact details in `contact.html`.

## To preview locally
Just open `index.html` in a browser — no server needed. Or, for a local server:
```
cd site
python3 -m http.server 8000
```
then visit `http://localhost:8000`.

## To host for free on GitHub Pages
See the setup walkthrough in chat — short version:
1. Create a GitHub repo named `<your-username>.github.io`.
2. Push these files to the `main` branch.
3. In the repo's Settings → Pages, confirm the source is `main` / `root`.
4. Your site is live at `https://<your-username>.github.io`.
