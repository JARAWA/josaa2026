# JoSAA 2025 — College Predictor

A fast, client-side college predictor for JEE students across all IITs, NITs, and IIITs — with admission probabilities, smart insights, charts, and a suggested preference list.

## 🚀 Live Demo

> Deployed via GitHub Pages at: `https://<your-username>.github.io/<repo-name>/`

## 📁 Repository Structure

```
├── index.html   # Full app (HTML + CSS + JS, single file)
└── data.json    # Cutoff data — 10,436 records, Round 6
```

## ⚙️ Deploying to GitHub Pages

1. **Create a new repo** (or push to an existing one)
2. Upload both `index.html` and `data.json` to the root of the `main` branch
3. Go to **Settings → Pages**
4. Under *Source*, select **Deploy from a branch**
5. Choose **`main`** branch and **`/ (root)`** folder → click **Save**
6. Your site will be live at `https://<username>.github.io/<repo>/` within ~60 seconds

## ✨ Features

- 🟢 **Safe / 🟡 Target / 🔴 Dream / ⭐ Hidden Gem** predictions
- Filters by Category, Gender, Quota, Institute Type, Branch, and State
- Rank buffer slider for cutoff flexibility
- Admission probability bar per result
- 4 interactive charts (donut, bar, horizontal bar, scatter)
- Smart insights summary
- Suggested preference list (auto-ordered)
- Search + pagination across all results
- CSV export of filtered results
- Fully responsive (mobile-friendly)

## 🔒 Privacy

All processing is 100% client-side. No data is sent to any server.
