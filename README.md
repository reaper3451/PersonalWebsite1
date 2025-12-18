Demo clone of https://www.ciccarello.me/

This repository contains a minimal static HTML/CSS scaffold that reproduces the site's structure (hero, skills, posts, connect) using placeholder content. It does NOT copy long original text or images.

To preview locally:

```bash
# from repository root
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Next steps:
- Confirm whether you want exact content copied (you must have permission) or placeholders
- Replace placeholder content and images with real content
- Add blog engine or RSS if desired

Course checklist & deployment
- Ensure the repository is public on GitHub.
- Projects page with Project 1 and Project 2 (placeholders) is included: `projects.html`.
- Navigation bar, footer, and social icons are present.
- Placeholder screenshots are in `assets/` (see `screenshot1.svg`, `screenshot2.svg`).
- Responsive styles are included in `styles.css` (mobile adjustments).

Git quick-commands (do these often when making changes):

```bash
git status
git add .
git commit -m "Describe your changes"
git push
```

If you haven't pushed the repo yet, from project root:

```bash
git init
git add .
git commit -m "Initial scaffold clone"
git branch -M main
git remote add origin https://github.com/<your-username>/ciccarello-clone.git
git push -u origin main
```

When finished, enable GitHub Pages in repository Settings → Pages → Branch `main` + folder `/ (root)`.

If you want, I can replace the `VIDEO_ID` placeholders with real IDs and update the repo link to your actual GitHub URL.
