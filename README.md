# VA Systems Portfolio — Loragine Tayad (Louie)

Static, single-page portfolio for Louie’s side-income VA + AI/automation offers.

**Hard constraints baked in:** no employer names, no real client/stakeholder data, no monday board IDs. monday.com may appear as a CRM skill. Demo content is synthetic (Acme, River Studio, etc.).

## Local preview

```bash
cd louie-portfolio
python3 -m http.server 8080
# open http://localhost:8080
```

## Deploy to GitHub Pages (free)

1. Create a **public** repo under your hustle GitHub account (e.g. `va-systems-portfolio`).
2. From this folder:

```bash
git init
git add index.html styles.css README.md
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/<YOUR_USER>/va-systems-portfolio.git
git push -u origin main
```

3. In the repo on GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` / root (`/`)
4. Wait ~1 minute. Live URL will be:

`https://<YOUR_USER>.github.io/va-systems-portfolio/`

### Optional: custom domain

Add a `CNAME` file with your domain, then point DNS (A/ALIAS or CNAME) per GitHub Pages docs.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full portfolio page |
| `styles.css` | Dark elegant theme |
| `LINKEDIN_DRAFT.md` | Draft profile copy — **do not publish without Louie approval** |
| `README.md` | This file |

## Contact (on site)

- LinkedIn: https://www.linkedin.com/in/loragine/
- Email: freelanceloes@gmail.com
