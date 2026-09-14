# அண்ணா பட்டு மையம் — Website

Static website for Anna Pattu Centre (Darasuram, Kumbakonam).

## Folder structure
```
anna-pattu-site/
├── index.html        (the website)
├── vercel.json        (hosting config)
└── images/
    ├── saree-red.png
    ├── saree-green.png
    └── saree-purple.png
```

## 1. GitHub-ல upload panna (website ah repo aakka)

1. https://github.com ku poi login pannunga (illa na account create pannunga).
2. Top-right "+" icon → **New repository** click pannunga.
3. Repository name: `anna-pattu-site` (or edhavadhu name) → **Create repository**.
4. Andha puthu repo page-la **"uploading an existing file"** link click pannunga.
5. Indha folder full-a (index.html, vercel.json, images/ folder ellam) drag & drop pannunga.
6. Kீழ **Commit changes** button click pannunga.

(Terminal use pannuna, indha commands run pannunga andha folder-ku poi:)
```bash
git init
git add .
git commit -m "Anna Pattu Centre website"
git branch -M main
git remote add origin https://github.com/<your-username>/anna-pattu-site.git
git push -u origin main
```

## 2. Vercel-la deploy panna

1. https://vercel.com ku poi, **"Continue with GitHub"** vachi login pannunga.
2. Dashboard-la **Add New → Project** click pannunga.
3. Neenga import panna `anna-pattu-site` GitHub repo select pannunga → **Import**.
4. Framework: **Other** (static site) nu automatic-a detect aagum, edhuvum maatha vendam.
5. **Deploy** click pannunga.
6. 30 seconds-la unga website live aagidum — `anna-pattu-site.vercel.app` mathiri oru link kudukum.

## 3. Update panna venumna (future)

Edha maatta venumna, `index.html` file-ah edit pannitu, andha same GitHub repo-la commit push pannunga — Vercel automatic-a redeploy aagidum.
