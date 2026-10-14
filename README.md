# Phuoc Nguyen — academic website starter

A five-page static academic site tailored from Phuoc Nguyen's publicly documented Deakin University profile (reviewed October 2026).

## Included

- `index.html` — concise homepage, selected publications and research themes
- `research.html` — three research directions
- `publications.html` — six verified DOI links
- `students.html` — prospective PhD information and publicly listed current/completed supervision
- `about.html` — biography, research projects, contact and academic profile links
- `portrait.png` — portrait displayed on the homepage and biography page
- `assets/style.css` — responsive styling

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `YOUR-GITHUB-USERNAME.github.io` (use your exact GitHub username).
2. Unzip this package, and upload the *contents* of the `phuoc-academic-site` folder into the repository root. `index.html` must be in the root.
3. In repository **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/(root)` and Save.
4. After GitHub publishes it, open `https://YOUR-GITHUB-USERNAME.github.io/`.

### Git commands

```bash
cd phuoc-academic-site
git init
git branch -M main
git add .
git commit -m "Launch academic website"
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/YOUR-GITHUB-USERNAME.github.io.git
git push -u origin main
```

Create the GitHub repository first, without an auto-generated README or license, to avoid initial commit conflicts.

## Local preview

```bash
cd phuoc-academic-site
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Before announcing the site

- The homepage and biography page use `portrait.png`, displayed at a compact width of 148 pixels. Replace that file to update the photo, and update the image width and height attributes if its dimensions change.
- Confirm official title, publication information, research topics and student statuses, and keep them current.
- Check PhD scholarship availability **before** announcing funded opportunities. This starter makes no such claim.
- Add your actual LinkedIn URL only after verifying it. The uploaded PDF was of a LinkedIn feed, not a profile page.
- Optionally add a CV PDF in `assets/` with permission to publish it.
- If your GitHub handle is not yet decided, the site works for any user-level repository named `username.github.io`.

## Verified sources

- Deakin profile: https://experts.deakin.edu.au/37836-phuoc-nguyen/about
- Research outputs: https://experts.deakin.edu.au/37836-phuoc-nguyen/publications
- Research grants: https://experts.deakin.edu.au/37836-phuoc-nguyen/grants
- Doctoral supervision: https://experts.deakin.edu.au/37836-phuoc-nguyen/teaching
- Google Scholar: https://scholar.google.com/citations?user=c4LnrZ0AAAAJ&hl=en
- ORCID: https://orcid.org/0000-0002-1649-2519
- University application guide: https://www.deakin.edu.au/research/research-degrees/how-to-apply-for-a-research-degree

This is a personal academic website, not an official Deakin University website.
