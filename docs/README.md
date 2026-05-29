# GitHub Pages deployment folder

This folder is ready for GitHub Pages.

In your GitHub repository, go to:

Settings → Pages → Build and deployment → Deploy from a branch

Then choose:

- Branch: `main`
- Folder: `/docs`

The app runs directly from `docs/index.html`.

## v2 bug fixes

- Staff speech bubbles now appear above the placeholder images, in italic speech marks.
- The next step no longer appears immediately after clicking Samira; a Next button appears only after all three staff responses have been opened.
- Becca Richardson’s email now appears above Chris Doogan’s email because it is the most recent message.


## v3 note

This version includes cache-busting file references and a small `v3` marker on the staff-check task screen so it is easy to confirm GitHub Pages is serving the updated files.
