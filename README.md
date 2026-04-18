# ⚡ Shane Lazar — Personal Portfolio

> **Dark cyberpunk-themed developer portfolio** built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies — just one file, zero build steps.

---

## 👤 About

This is the source code for my personal portfolio website. It showcases my background as a **Senior Data Analyst**, **Software Developer**, **Data Engineer**, and **Web Developer** — with a focus on data-driven roles in healthcare, public sector, and mission-driven organisations.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎯 Custom Cursor | Neon dot + trailing ring that reacts to hover |
| 🌌 Parallax Scrolling | Floating glyphs and layers move at different depths |
| 📊 Animated Skill Bars | Fire on scroll into view via IntersectionObserver |
| 🕐 Experience Timeline | Pulsing neon dots with staggered fade-in |
| 📱 Responsive | Mobile-friendly layout with adapted navigation |
| 🔲 Scanline Overlay | CRT-style texture for the cyberpunk aesthetic |
| 🔠 Google Fonts | Orbitron · Share Tech Mono · Rajdhani |
| 💡 Zero Dependencies | Pure HTML/CSS/JS — no npm, no build tools |

---

## 🗂️ Sections

- **Hero** — Name, tagline, CTA buttons
- **About Me** — Bio, animated hexagon visual, key stats
- **Skills & Tech Stack** — 8 skill cards with progress bars
- **Projects** — 3 featured projects with tech tags
- **Work Experience** — Animated timeline with 3 roles
- **Education** — Degree cards for University of Leicester & St Xavier's College
- **Contact** — Email, LinkedIn, and GitHub links

---

## 🛠️ Tech Stack

```
HTML5      — Semantic structure
CSS3       — Custom properties, animations, parallax, grid layout
JavaScript — IntersectionObserver, requestAnimationFrame, scroll events
Google Fonts — Orbitron, Share Tech Mono, Rajdhani (loaded via CDN)
```

---

## 🚀 Deployment

This portfolio is a single `index.html` file — it can be deployed anywhere static files are supported.

### Option 1 — Netlify (Recommended)
1. Go to [netlify.com](https://netlify.com) and sign up for free
2. Drag and drop `index.html` onto the Netlify deploy zone
3. Your site is live instantly at `your-name.netlify.app`
4. Rename it under **Site Settings → Change site name**

### Option 2 — GitHub Pages
1. Create a repo named `shanelazar.github.io`
2. Push `index.html` to the `main` branch
3. Go to **Settings → Pages → Source → main branch**
4. Site goes live at `shanelazar.github.io`

### Option 3 — Any Static Host
Works on Vercel, Cloudflare Pages, Render, or any web server — just upload the file.

---

## 📁 Project Structure

```
📦 portfolio/
 ┣ 📄 index.html      ← Entire portfolio (HTML + CSS + JS in one file)
 ┗ 📄 README.md       ← You are here
```

> All styles and scripts are embedded directly in `index.html` for maximum portability.

---

## 🎨 Design Decisions

- **Aesthetic:** Dark cyberpunk / retro-futuristic terminal
- **Palette:** `#00f5ff` Cyan · `#ff00c8` Magenta · `#7b2fff` Purple · `#00ff88` Green on `#020408` near-black
- **Typography:** `Orbitron` for headings (bold, geometric, futuristic) · `Share Tech Mono` for labels and code-like text · `Rajdhani` for body copy
- **No frameworks** — keeps load time minimal and the portfolio fully self-contained

---

## ✏️ Customisation

To update your portfolio, open `index.html` in any text editor and find the relevant section:

| What to change | Where to find it |
|---|---|
| Name / tagline | `<!-- HERO -->` section |
| About Me text | `<!-- ABOUT -->` section |
| Skills | `<!-- SKILLS -->` section — edit `skill-name`, `skill-desc`, and bar `width` |
| Projects | `<!-- PROJECTS -->` section |
| Work experience | `<!-- EXPERIENCE -->` section |
| Education | `<!-- EDUCATION -->` section |
| Contact links | `<!-- CONTACT -->` section — update `href` attributes |
| Colour scheme | `:root` CSS variables at the top of `<style>` |

---

## 📬 Contact

| Platform | Link |
|---|---|
| 📧 Email | [lazarshane21@gmail.com](mailto:lazarshane21@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/shane-lazar](https://www.linkedin.com/in/shane-lazar) |
| 🐙 GitHub | [github.com/shanelazar](https://github.com/shanelazar) |

---

<p align="center">
  Built with ❤️ and a lot of neon by <strong>Shane Lazar</strong> · 2025
</p>
