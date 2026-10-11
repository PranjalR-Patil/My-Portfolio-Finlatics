# Pranjal Patil — Portfolio

Personal portfolio site for **Pranjal Patil**, an aspiring software engineer.

Sections: hero, about, projects (Vendor Vantage, Aqua Intel AI, Crime Investigation System), contact. Built with HTML, Tailwind CSS (CDN) and a little CSS/JS.

## Structure

```
personal-portfolio/
├── index.html
├── styles.css
├── package.json
├── assets/
│   ├── profile.svg
│   ├── project-1.svg
│   ├── project-2.svg
│   └── project-3.svg
├── .gitignore
└── README.md
```

## Run locally

```bash
npm install
npm start
```

Open the URL shown in the terminal (usually `http://localhost:3000`). You can also open `index.html` directly in a browser.

## Push to GitHub

```bash
git init -b main
git add .
git commit -m "Add personal portfolio site"
git remote add origin https://github.com/PranjalR-Patil/personal-portfolio.git
git push -u origin main
```

Create the empty repo on GitHub first (no README, no .gitignore).

## Deploy on Vercel (when ready)

Import the repo on vercel.com, framework preset **Other**, leave build command and output directory empty.

## Customize

- Profile photo: put a photo in `assets/` and change `src="assets/profile.svg"` in `index.html`.
- Project links: search `Repo coming soon` in `index.html` and replace with a GitHub button.
