# F.F. Feriozzi Orafi — Static Website

Static website for F.F. Feriozzi Orafi, a family jewelry workshop in Rome. Built for hosting on GitHub Pages.

## Pages

- `index.html` — Home
- `about.html` — About us / Family tradition
- `creations.html` — Our creations (rings, necklaces, earrings, etc.)
- `contact.html` — Contact us (with map, contact form, details)
- `style.css` — All styles

## How to deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `feriozzi-site`)
2. Push all files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/YOUR_USERNAME/feriozzi-site.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your repo
4. Under **Source**, select `main` branch and root `/`
5. Click **Save** — your site will be live at `https://YOUR_USERNAME.github.io/feriozzi-site/`
