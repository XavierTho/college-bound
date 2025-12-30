# College Bound

Welcome to the College Bound website!

## 🌐 View Live Website

The website is automatically deployed to GitHub Pages and can be viewed at:

**https://xaviertho.github.io/college-bound/**

## 🚀 Deployment

This website is automatically deployed using GitHub Actions whenever changes are pushed to the `main` branch.

### How it Works

1. When you push changes to the `main` branch, GitHub Actions automatically triggers the deployment workflow
2. The workflow builds and deploys the website to GitHub Pages
3. Your changes will be live within a few minutes

### Manual Deployment

You can also trigger a manual deployment:

1. Go to the [Actions tab](https://github.com/XavierTho/college-bound/actions)
2. Select the "Deploy to GitHub Pages" workflow
3. Click "Run workflow"

## 📋 Setup Instructions (One-time)

To enable GitHub Pages for this repository:

1. Go to your repository settings: https://github.com/XavierTho/college-bound/settings/pages
2. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"
3. The workflow will automatically deploy on the next push to `main`

## 🛠️ Local Development

To view the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/XavierTho/college-bound.git
   cd college-bound
   ```

2. Open `index.html` in your web browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

   Or use a simple HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then visit http://localhost:8000
   ```

## 📝 Making Changes

1. Edit the `index.html` file
2. Commit your changes:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```
3. The website will automatically update on GitHub Pages within a few minutes

## 🔧 Technologies

- HTML5
- GitHub Pages
- GitHub Actions (for CI/CD)
