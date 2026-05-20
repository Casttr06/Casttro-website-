# CASTTRO site upload guide

## GitHub Pages
1. Create a new public GitHub repository.
2. Upload `casttro-artist-site.html` and the full `assets` folder.
3. Rename `casttro-artist-site.html` to `index.html` inside the repo.
4. Go to Settings -> Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select `main` and `/root`, then Save.
7. Wait for the Pages URL to appear.

## Cloudflare Pages
1. Create a new GitHub repo and upload the same files.
2. In Cloudflare Pages, choose Create application -> Pages -> Import an existing Git repository.
3. Select the repo.
4. Production branch: `main`.
5. Build command: leave empty or use `exit 0`.
6. Build output directory: `/`.
7. Deploy to get a `.pages.dev` live URL.

## Contact form
Right now the form opens a pre-filled email draft. You can later switch it to Formspree if you want direct submissions from the site.
