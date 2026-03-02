# Steven Archive

## Structure

```
BLOG/
├── index.html          # Front page
├── css/
│   └── style.css       # All styles
├── about/              # About page
├── learning/           # Learning notes & tutorials
└── paper-reviews/      # Paper summaries & analysis
```

## Deploy to GitHub Pages

1. **Create a GitHub repo** (e.g. `yourusername.github.io` for a user site, or `blog` for a project site)

2. **Push this folder** to the repo:
   ```bash
   cd BLOG
   git init
   git add .
   git commit -m "Initial blog setup"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to **Settings → Pages**
   - Under "Source", choose **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)`
   - Save

4. **View your site** at:
   - User site: `https://yourusername.github.io`
   - Project site: `https://yourusername.github.io/blog` (or your repo name)

## Customize

- **Name & links**: Replace "Your Name" and placeholder URLs in `index.html` and section pages
- **Intro text**: Edit the `.intro-section` in `index.html`
- **Content**: Add real posts to each section and link them from the front page
