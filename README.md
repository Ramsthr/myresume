# Ram — Resume Site

A minimal portfolio/resume site inspired by [nishchay17.com](https://nishchay17.com/).

## Features
- Dark / Light mode (auto-detects OS preference, persists to localStorage)
- Command palette (`⌘K` / `Ctrl+K`) with search and navigation
- Sticky sidebar with active-section highlighting
- Fully responsive (sidebar hides on mobile)
- Single `index.html` — no build step needed

## Deploying to GitHub Pages

### Option A — New repo (simplest)
1. Create a new **public** GitHub repository named `<your-username>.github.io`  
   *(e.g. `ram123.github.io`)*
2. Push this repo to it:
   ```bash
   git init
   git add .
   git commit -m "init: resume site"
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. Your site will be live at `https://<your-username>.github.io` within a minute or two.

### Option B — Any repo (project site)
1. Push to any GitHub repo.
2. Go to **Settings → Pages → Source**, choose `main` branch, root `/`.
3. Site will be at `https://<your-username>.github.io/<repo-name>/`.

---

## Personalising the content

Open `index.html` and update these sections:

| What to change | Where in the file |
|---|---|
| Name & hero tagline | `.hero-heading` and `.hero-intro` |
| Job title, company, location | `#overview` section |
| LinkedIn & email | `#overview` section |
| About bullet points | `#about` section |
| Tech stack pills | `#stack` section |
| Work experience | `#experience` section |
| Projects (name, link, description) | `#projects` section — also update `projects(3)` count |
| GitHub / LinkedIn links | `#contact` section + `footer` |

Search for `YOUR_GITHUB` and `YOUR_USERNAME` in the file to find every placeholder link.
