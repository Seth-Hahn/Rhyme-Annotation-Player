# MUSC 120 RAP — Rhyme Annotation Player

A browser-based tool for annotating rap lyrics, beats, and literary devices.

**Live app (after you publish):** `https://YOUR-GITHUB-USERNAME.github.io/musc120-rap/`

---

## Publish to GitHub Pages (one-time setup)

### 1. Create a GitHub repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `musc120-rap` (or any name you like)
3. Set to **Public** (required for free GitHub Pages)
4. Do **not** add a README (this folder already has one)
5. Click **Create repository**

### 2. Push this folder to GitHub

In Terminal, run (replace `YOUR-GITHUB-USERNAME` with your GitHub username):

```bash
cd "/Users/sethhahn/Downloads/important_documnets/Prof Naru Rap Website"

git init
git add index.html README.md .gitignore
git commit -m "Add RAP annotator for GitHub Pages"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/musc120-rap.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Open your repo on GitHub → **Settings** → **Pages**
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Click **Save**
5. Wait 1–2 minutes. Your site will be at:

   `https://YOUR-GITHUB-USERNAME.github.io/musc120-rap/`

### 4. Update the app

After editing `index.html` (or `RAP_V3.html` then copy to `index.html`):

```bash
git add index.html
git commit -m "Update RAP"
git push
```

Changes go live in about a minute.

---

## For students (simple)

1. Open the class link (or scan the QR code from **Share / QR**)
2. Annotate directly on the grid
3. Use **+** to add your own board tab if working in groups
4. **Export CSV** to turn in your work

No Terminal, no local server, no file downloads required.

---

## For instructors

- Open the hosted URL (not the file from Downloads)
- Click **Share / QR** — the QR code works on any phone or laptop
- Students who scan join the same board room; cloud sync loads your starting grid
- Use **Compare** to see differences between student tabs

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | Published version (GitHub Pages serves this) |
| `RAP_V3.html` | Working copy for local edits |

After editing `RAP_V3.html`, copy it to `index.html` before pushing:

```bash
cp RAP_V3.html index.html
```
