# Personal Resume Website

A simple three-page personal resume website built with HTML and CSS for the university tutorial.

## Files
- `index.html` — Home / resume
- `hobbies.html` — Hobbies and interests
- `contact.html` — Contact details
- `style.css` — Shared styling for all pages

## Before publishing
1. Replace `[Your Name]` with your name.
2. Add your matric number where required by your lecturer (it is not displayed publicly by default).
3. Replace the sample email, GitHub and LinkedIn links in `contact.html`.
4. Update expected graduation year and check that every listed skill and project accurately reflects your experience.
5. Edit the hobbies page to include your actual hobbies.

## Run locally
Open `index.html` in a web browser. All three pages should be navigable using the menu.

## Publish with GitHub Pages
Create an empty repository on GitHub, for example `my-resume-site`. In the folder containing these files, run:

```bash
git init
git add .
git commit -m "Initial resume site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/my-resume-site.git
git push -u origin main
```

Then open **Settings → Pages** on GitHub. Select **Deploy from a branch**, choose `main` and `/(root)`, then save. Your site will be available at:

`https://YOUR-USERNAME.github.io/my-resume-site/`

## Important Git instruction correction
The tutorial's Git commands are valid if the repository is empty and the remote URL is correct. If the GitHub repository was created with a README, licence or `.gitignore`, it is not truly empty and may already have a commit. In that case, pushing a separate local history can be rejected as a non-fast-forward update. Create an empty repository as instructed, or pull and reconcile the remote history before pushing. Also replace `<yourusername>` with your actual GitHub username; do not type the angle brackets.
