# Feasto Project Task List

Use this checklist to track improvements you want to make to the project.

## Layout & Navigation

- [ ] Make the header (logo + nav menu) exactly the same in all 3 pages: `index.html`, `order.html`, `feedback.html`.
- [ ] Make the footer (About / Contact / Follow Us) exactly the same in all 3 pages.
- [ ] On every page, make the logo clickable so it takes the user to the home section:
  - `index.html` → scroll to `#home`.
  - `order.html` and `feedback.html` → go to `index.html#home`.

## Responsiveness

- [ ] Ensure the project is responsive on all devices (mobile, tablet, desktop):
  - [ ] Navbar wraps or turns into a mobile-friendly layout.
  - [ ] Hero / welcome section scales well on small screens.
  - [ ] Order form and feedback card look good on phones.

## Internal Links (About / Contact)

- [ ] When you are on `order.html` and click **About** or **Contact`, it should show the About/Contact sections on the same page (not jump back to `index.html`).
- [ ] Decide how to implement this:
  - Option A: Add local `#about` and `#contact` sections into `order.html` and link to them.
  - Option B: Keep About/Contact only on `index.html` but open them in a new tab if you prefer.

## Visual Improvements

- [ ] Add or refine a background image behind the welcome statement in the intro area of `index.html` ("Welcome to Feasto !!" section) so it looks clean on all screen sizes.

## GitHub Deployment

- [ ] Implement step-by-step deployment to GitHub:
  1. Create a GitHub account (if you don’t have one).
  2. Create a new repository (for example: `feasto-food-ordering`).
  3. In VS Code / terminal, initialize Git in this folder: `git init`.
  4. Add all files and commit: `git add .` then `git commit -m "Initial commit"`.
  5. Connect to GitHub: `git remote add origin <your-repo-URL>`.
  6. Push the code: `git push -u origin main` (or `master` depending on your repo).
  7. For GitHub Pages: in the repo Settings → Pages → select the branch (e.g. `main`) and root folder, then save.
  8. Wait for the GitHub Pages URL and test the live site.

## Documentation

- [ ] Keep `README.md` updated with:
  - Short project description.
  - Main files / folders.
  - Basic "how to run" and "how to deploy" notes.
