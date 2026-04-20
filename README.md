# Birthday Surprise - Deployment

This project is a static website.

## Quickest public deploy (no code changes)

1. Open https://app.netlify.com/drop
2. Drag the project folder into the page:
   - `birthday/`
3. Netlify gives you a public URL instantly.

## GitHub Pages deploy (recommended for permanent hosting)

1. Create a new GitHub repository (for example: `birthday-surprise`).
2. In this project folder, run:

```powershell
git init
git add .
git commit -m "Initial birthday site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

3. In GitHub:
   - Go to repository Settings > Pages
   - Source: Deploy from a branch
   - Branch: `main` and folder `/ (root)`
4. Save. Your site will be live at:
   - `https://<your-username>.github.io/<your-repo>/`

## Vercel deploy

1. Go to https://vercel.com/new
2. Import your GitHub repo.
3. Framework preset: `Other` (or auto-detected static).
4. Deploy.

## Notes

- Entry file is `index.html`, which most static hosts require.
- Original file `bir.html` is still preserved.
