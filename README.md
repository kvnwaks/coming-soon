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

This repository uses GitHub Actions to automatically deploy to GitHub Pages whenever you push to the `main` branch.

### Initial Setup

1. **Enable GitHub Pages**
   - Go to your repository's **Settings** → **Pages**
   - Under **Source**, select **Deploy from a branch**
   - Select the **gh-pages** branch
   - Click **Save**

2. **Create the gh-pages branch** (if it doesn't exist)
   - Go to **Actions** tab
   - Select the **Deploy to GitHub Pages** workflow
   - Click **Run workflow**
   - This will create the `gh-pages` branch and deploy your site

Your site will be available at `https://your-username.github.io/repository-name/`

### Custom Domain (Optional)

To use a custom domain:

1. **Add your domain as a repository variable**
   - Go to **Settings** → **Secrets and variables** → **Actions** → **Variables** tab
   - Click **New repository variable**
   - Name: `CNAME`
   - Value: your domain (e.g., `example.com`)
   - Click **Add variable**

2. **Configure GitHub Pages**
   - Go to **Settings** → **Pages**
   - Under **Custom domain**, enter your domain
   - Click **Save**

### How It Works

- The workflow automatically deploys your site from the `src` folder to the `gh-pages` branch
- Your `main` branch remains unchanged, keeping it clean and easy to sync if forked
- Any changes to `main` trigger an automatic deployment
- The `gh-pages` branch contains only the deployed site files

## License

MIT
