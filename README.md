# P4V3R's Y2K Portfolio Site

**A portfolio website with late 90s/early 2000s aesthetic**

---

## 🌐 Live Site

**URL:** https://p4v3r.github.io

---

## 📋 Pages

| Page | Description |
|------|-------------|
| `index.html` | Home - Hero, quick projects, currently working/watching |
| `projects.html` | All GitHub projects with personal reviews |
| `about.html` | Setup: macOS, Coding, Privacy & Security |
| `favorites.html` | Games, Anime, Manga, Movies, Music, Artists |
| `watching.html` | Currently watching anime, movies, series |
| `blog.html` | Blog posts |

---

## ⚙️ Configuration

All content is driven by JSON config files in `_config/`:

| File | Content |
|------|---------|
| `_config/projects.json` | GitHub projects with personal descriptions |
| `_config/favorites.json` | All your favorites by category |
| `_config/setup.json` | macOS, Coding, Privacy setup |
| `_config/links.json` | Social links and contact |
| `_config/currently.json` | Currently working on / watching |

---

## 🎨 Aesthetic

Y2K meets Cyberpunk meets Anime 90s:

- `<marquee>` scrolling banners
- Neon color palette (pink, purple, cyan)
- Scanline effects
- Hit counters (fake, stored in localStorage)
- "Under construction" sections
- Table-based layouts
- Glitch text animations

---

## 📁 Project Structure

```
p4v3r.github.io/
├── index.html          # Main page
├── projects.html       # Projects page
├── about.html          # Setup page
├── favorites.html      # Favorites page
├── watching.html       # Currently watching
├── blog.html           # Blog index
├── blog/
│   ├── privacy-matters.md
│   └── y2k-portfolio.md
├── _config/
│   ├── projects.json
│   ├── favorites.json
│   ├── setup.json
│   ├── links.json
│   └── currently.json
├── css/
│   └── style.css       # Y2K styling
├── .nojekyll           # Prevent Jekyll processing
└── README.md
```

---

## 🔒 Privacy

- No tracking scripts
- No analytics
- No cookies
- No data collection
- Pure static HTML only

---

## 📜 License

MIT - Do whatever you want with it.
