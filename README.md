# Hariharan — Portfolio Website

Personal portfolio for **Hariharan T** — Web Developer & SEO Specialist based in Coimbatore, India.

🌐 **Live site:** [hariharan84.github.io](https://hariharan84.github.io)

---

## Pages

| File | URL |
|------|-----|
| `index.html` | `hariharan84.github.io/` |
| `portfolio/index.html` | `hariharan84.github.io/portfolio/` |

## Folder Structure

```
hariharan84.github.io/
├── index.html           ← Home page
├── portfolio/
│   └── index.html       ← Portfolio page
├── images/
│   ├── drpals.avif
│   ├── explicit-finance.avif
│   ├── labxcite.avif
│   └── wployalty.avif
├── .nojekyll            ← Disables Jekyll processing
└── README.md
```

## Adding a New Project

Open `portfolio/index.html` and find the comment block:

```
/* ADD PROJECT HERE */
```

Copy the project card template in that section, fill in:
- `href` → live project URL
- `data-category` → one or more of: `wordpress shopify ecommerce seo software`
- `src` → path to screenshot in `images/` folder (use `../images/filename.avif`)
- Project name, description, tags

## Deploying to GitHub Pages

1. Create a repo named **exactly** `hariharan84.github.io` on GitHub
2. Push all files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/hariharan84/hariharan84.github.io.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source → Deploy from branch → main / (root)**
4. Site goes live at `https://hariharan84.github.io` within ~60 seconds

## Tech

- Pure HTML, CSS, JavaScript — no frameworks
- Google Fonts only (Syne, DM Mono, Cabinet Grotesk)
- WCAG AA accessible (contrast ratios 4.5:1+, skip link, focus styles)
- Mobile responsive with hamburger menu
