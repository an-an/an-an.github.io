# an-an.github.io

Personal homepage for [https://an-an.github.io/](https://an-an.github.io/).

## Publish to GitHub Pages

1. **Create a repo** on GitHub named exactly `an-an.github.io` (same as your username).
2. **Push this project** to that repo:
   ```bash
   git init
   git add .
   git commit -m "Initial homepage"
   git branch -M main
   git remote add origin https://github.com/an-an/an-an.github.io.git
   git push -u origin main
   ```
3. **Settings → Pages**: Source = “Deploy from a branch”, Branch = `main`, folder = `/ (root)`, then Save.
4. After a minute or two, the site will be live at **https://an-an.github.io/**.

## Edit the page

- Update `index.html`: change the name, tagline, bio, and add your real links (GitHub, email, etc.).
- No build step — edit HTML/CSS and push to `main` to update the site.
