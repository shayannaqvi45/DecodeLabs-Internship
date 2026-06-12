# Syed Muhammad Shayan Naqvi — Portfolio Website

A premium, fully responsive personal portfolio website with dark glassmorphism design, smooth animations, and all assets embedded directly in a single HTML file.

---

## 🚀 Features

- ✅ Dark theme with glassmorphism effects
- ✅ Smooth scroll animations (Intersection Observer)
- ✅ Scroll progress indicator
- ✅ Mobile-responsive with hamburger menu
- ✅ Profile photo embedded (no external dependencies)
- ✅ All 3 project screenshots embedded
- ✅ Animated skill progress bars
- ✅ Copy-to-clipboard for contact info
- ✅ Contact form (opens email client pre-filled)
- ✅ Toast notifications
- ✅ Back-to-top button
- ✅ SEO + Open Graph meta tags
- ✅ Zero build step — single `.html` file

---

## 📁 File Structure

```
portfolio.html    ← Everything in one file (self-contained)
README.md         ← This file
```

---

## 🖥️ Local Preview

Simply open `portfolio.html` in any modern browser:

```bash
# macOS
open portfolio.html

# Windows
start portfolio.html

# Linux
xdg-open portfolio.html
```

Or use VS Code Live Server for hot-reload during edits.

---

## 🌐 Deploy to GitHub Pages (Free)

1. Create a new GitHub repository (e.g. `my-portfolio`)
2. Upload `portfolio.html` and rename it to `index.html`
3. Go to **Settings → Pages**
4. Set source to `main` branch, `/ (root)` folder
5. Click **Save** — your site will be live at `https://shayannaqvi45.github.io/my-portfolio/`

---

## 🔺 Deploy to Vercel (Free)

1. Install Vercel CLI: `npm i -g vercel`
2. Rename `portfolio.html` → `index.html`
3. In the same folder, run:
   ```bash
   vercel
   ```
4. Follow the prompts — Vercel auto-detects a static site
5. Your site goes live instantly with a `.vercel.app` URL

Or drag-and-drop the folder at **vercel.com/new** (no CLI needed).

---

## 🟢 Deploy to Netlify (Free)

**Option A — Drag & Drop:**
1. Go to [netlify.com](https://netlify.com) → Log in
2. Drag your folder containing `index.html` to the deploy zone
3. Live in seconds at a `.netlify.app` URL

**Option B — CLI:**
```bash
npm i -g netlify-cli
netlify deploy --dir . --prod
```

---

## ✏️ Customization Guide

| What to change | Where to find it |
|---|---|
| Name / title / bio | Search `hero-content` section in HTML |
| Profile photo | Replace the `src` of `.hero-img` |
| Project screenshots | Replace `src` of each `.project-img-wrap img` |
| Skills & percentages | Edit `data-width` on each `.skill-fill` div |
| Project links | Update `href` on `.proj-btn` anchors |
| Colors | Edit CSS variables in `:root` block |
| Contact info | Search `shayannaqvi45@gmail.com` |

---

## 🎨 Color Palette

| Variable | Hex | Use |
|---|---|---|
| `--accent` | `#6c63ff` | Primary purple |
| `--accent2` | `#a78bfa` | Soft violet |
| `--accent3` | `#38bdf8` | Sky blue |
| `--bg` | `#080b14` | Main background |
| `--text` | `#f1f5f9` | Body text |

---

## 📝 License

Personal use only. All content belongs to Syed Muhammad Shayan Naqvi.
