# Sencillo Dzyns - GitHub Pages Deployment

This site is deployed using GitHub Pages with GitHub Actions.

## Setup Instructions

1. **Push to GitHub**: Commit and push all changes to the `main` branch
2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under **Source**, select **GitHub Actions**
   - The workflow will automatically deploy on push to main

## Deployment Process

The site uses GitHub Actions workflow (`.github/workflows/deploy.yml`) that:
- Triggers on push to main branch
- Uploads the entire repository as a Pages artifact
- Deploys to GitHub Pages

## Benefits of GitHub Pages

- ✅ **No filename restrictions** - Handles WordPress query parameters perfectly
- ✅ **Automatic deployment** - Deploys on every push to main
- ✅ **Free hosting** - No cost for public repositories
- ✅ **Custom domain support** - Can use your own domain
- ✅ **HTTPS included** - Automatic SSL certificates

## Your Site URL

After deployment, your site will be available at:
`https://[username].github.io/[repository-name]/`

Replace `[username]` and `[repository-name]` with your actual GitHub username and repository name.