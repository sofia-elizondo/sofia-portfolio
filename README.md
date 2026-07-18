# Sofia Elizondo — Portfolio

A static HTML/CSS site, ready to publish on GitHub Pages. No build step, no dependencies — just plain files.

## File structure

```
index.html          Home
about.html           About
work.html            Work (project grid)
contact.html         Contact
work/                Individual case study pages
css/style.css        All styles
js/main.js           Mobile nav toggle
```

## Publish it on GitHub Pages

1. Create a new repository on GitHub (e.g. `sofia-portfolio`). Don't initialize it with a README.
2. On your computer, open a terminal in this folder and run:
   ```
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/sofia-portfolio.git
   git push -u origin main
   ```
3. On GitHub, go to your repo → **Settings** → **Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then your site will be live at:
   `https://YOUR-USERNAME.github.io/sofia-portfolio/`

### Using a custom domain (optional)
If you own a domain (e.g. sofiaelizondo.com), add a `CNAME` file in this folder containing just the domain, then point your domain's DNS to GitHub Pages (see GitHub's custom domain docs). Ask me if you want help with this step.

## Filling in the remaining case studies
Four project pages (Myra Vision, Creatives Connect, BG Design System, XDEMVY Social Posts) currently have short overviews because their Squarespace subpages were blocked from automated access. Paste the full write-ups to me and I'll drop them into the matching page in `work/`.
