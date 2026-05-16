# SennaFilter — Travel Photography Portfolio

## Folder Structure

```
sennafilter/
├── index.html
├── style.css
├── main.js
├── README.md
└── assets/              ← ALL your photos go here
    ├── hero.jpg          ← Homepage hero (full screen)
    ├── feature.jpg       ← "Feature My Work" section
    └── hotels/           ← Hotel photos
        ├── 0.jpg         ← Il Sereno cover
        ├── 1.jpg         ← Hotel Miramalfi cover
        ├── 2.jpg         ← Hotel Caesar Augustus cover
        ├── 3.jpg         ← Casa Angelina cover
        ├── 4.jpg         ← Château de Théoule cover
        ├── 5.jpg         ← Alisal Ranch cover
        │
        ├── 0-1.jpg       ← Il Sereno gallery photo 1
        ├── 0-2.jpg       ← Il Sereno gallery photo 2
        │   ... (0-1 through 0-18)
        ├── 1-1.jpg       ← Hotel Miramalfi gallery photo 1
        │   ... (1-1 through 1-17)
        ...and so on for each hotel (replace 0 with the hotel number)
```

## Notes
- If a photo is missing, the site shows a neutral color placeholder automatically.
- Photos can be JPG, PNG, or WebP — just keep the .jpg extension in the filename or update the JS.
- The hero image is already in place (assets/hero.jpg).

## Deploy to Vercel

1. Push this entire folder to a GitHub repository
2. Go to vercel.com → sign in with GitHub
3. Click "New Project" → import your repo
4. Leave all settings as default → Deploy
5. Your site will be live at `your-project.vercel.app`

To connect a custom domain (e.g. sennafilter.com):
- Go to your project in Vercel → Settings → Domains → Add your domain

## To Update

Edit files → push to GitHub → Vercel auto-deploys instantly.
