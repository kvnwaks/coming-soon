# Coming Soon

A simple "Work in Progress" page with an animated GIF display.

## About

The site displays a "Work in Progress" animated GIF on a black background. It's a minimalist placeholder page that can be used while developing or building out a website.

## Features

- Clean, centered GIF display
- Responsive design
- Dark theme with black background
- Automatic GitHub Pages deployment
- MIT Licensed - free to fork and modify

## Deployment

This repository uses GitHub Actions to automatically deploy to GitHub Pages.

1. Go to your repository's **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Select the **gh-pages** branch (if not present, manually trigger the repository's deployment workflow in the Actions tab — Actions → select the 'Deploy to GitHub Pages' workflow → "Run workflow" — this will create the gh-pages branch)
4. Click **Save**

The workflow will automatically deploy your site whenever you push to the `main` branch. Your site will be available at `https://your-username.github.io/repository-name/`

**Note:** The workflow keeps your `main` branch unchanged - it only creates/updates the `gh-pages` branch with the deployed site. This is particularly useful if you have a custom domain, as GitHub Pages may create a CNAME file in the deployment branch. By keeping changes isolated to the `gh-pages` branch, your `main` branch remains untouched and, if forked, can continue syncing from the source repo without conflicts.

## License

MIT
