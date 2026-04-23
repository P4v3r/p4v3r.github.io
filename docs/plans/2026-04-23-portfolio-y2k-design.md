# Portfolio Site Y2K Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Create a Y2K-styled portfolio website served on GitHub Pages with config-driven content.

**Architecture:** Static HTML/CSS/JS site with table-based Y2K layout. Content managed via JSON config files. No build step - direct GitHub Pages serving.

**Tech Stack:** HTML, CSS, JavaScript (vanilla), JSON config files

---

## Phase 1: Foundation

### Task 1: Create Project Structure & Configuration Files

**Files:**
- Create: `_config/projects.json`
- Create: `_config/favorites.json`
- Create: `_config/setup.json`
- Create: `_config/links.json`
- Create: `_config/currently.json`

**Step 1: Write all config files with example content**

```json
// _config/projects.json
[
  {
    "name": "void-sh",
    "title": "Secure In-Browser File Encryption",
    "description": "Client-side file encryption in the browser",
    "url": "https://github.com/P4v3r/void-sh",
    "language": "TypeScript"
  }
]
```

**Step 2: Commit**

```bash
cd /Users/Privacy/Documents/projects/portfolio-site
git add _config/*.json
git commit -m "feat: add config files structure"
```

---

### Task 2: Create Main CSS (Y2K Theme)

**Files:**
- Create: `css/style.css`

**Step 1: Write Y2K CSS with:**
- Table-based layout styles
- Neon color palette (purple, pink, cyan, black)
- Gradient backgrounds (cyber/vaporwave)
- Font imports (Impact, Verdana, Courier New)
- Marquee styling
- Hit counter styling
- Badge styling ("Best viewed in 1024x768")
- Responsive basics
- Animations (glitch, glow, float)

**Step 2: Commit**

```bash
git add css/style.css
git commit -m "feat: add Y2K CSS theme"
```

---

### Task 3: Create index.html (Main Page)

**Files:**
- Create: `index.html`

**Step 1: Write main page with:**
- Y2K doctype & structure
- Table-based layout
- Header with marquee welcome
- Avatar/name section
- Navigation bar (horizontal or vertical)
- Quick links to sections
- Footer with hit counter fake + badges
- Under construction elements
- Load config data via JS

**Step 2: Commit**

```bash
git add index.html
git commit -m "feat: add main index page"
```

---

### Task 4: Create JavaScript (Config Loader & Interactions)

**Files:**
- Create: `js/main.js`

**Step 1: Write JS with:**
- Fetch config files
- Render projects dynamically
- Render currently section
- Render links
- Hit counter increment (fake)
- Any marquee interactions
- MIDI player toggle (if wanted)

**Step 2: Commit**

```bash
git add js/main.js
git commit -m "feat: add JS config loader"
```

---

## Phase 2: Content Pages

### Task 5: Create projects.html

**Files:**
- Create: `projects.html`

**Step 1: Write page with:**
- Table layout consistent with index
- Project cards with Y2K styling
- Language badges
- Personal reviews
- Link to GitHub
- Back to home navigation

**Step 2: Commit**

```bash
git add projects.html
git commit -m "feat: add projects page"
```

---

### Task 6: Create about.html (Setup Page)

**Files:**
- Create: `about.html`

**Step 1: Write page with:**
- Setup categories: macOS, Coding Agent, Privacy/Security
- Table layout
- Equipment lists
- Software preferences
- Consistent Y2K styling

**Step 2: Commit**

```bash
git add about.html
git commit -m "feat: add setup/about page"
```

---

### Task 7: Create watching.html (Currently Watching)

**Files:**
- Create: `watching.html`

**Step 1: Write page with:**
- Categories: Anime, Movies, Series
- Card/grid layout
- Y2K styling
- Consistent navigation

**Step 2: Commit**

```bash
git add watching.html
git commit -m "feat: add watching page"
```

---

### Task 8: Create favorites.html

**Files:**
- Create: `favorites.html`

**Step 1: Write page with:**
- Categories: Games, Music, Artists, Movies, Manga, Anime
- Grid or table layout
- Y2K styling
- Consistent navigation

**Step 2: Commit**

```bash
git add favorites.html
git commit -m "feat: add favorites page"
```

---

### Task 9: Create blog.html & Blog Posts

**Files:**
- Create: `blog.html`
- Create: `blog/post-1.md`
- Create: `blog/post-2.md`

**Step 1: Write blog page with:**
- List of posts with dates
- Y2K styling
- Post content loaded from markdown (convert inline or use JS)
- Create 2 example blog posts

**Step 2: Commit**

```bash
git add blog.html blog/*.md
git commit -m "feat: add blog page and example posts"
```

---

## Phase 3: GitHub Pages Setup

### Task 10: Create CNAME & GitHub Config

**Files:**
- Create: `CNAME` (empty or with placeholder)
- Create: `.nojekyll` (prevents Jekyll processing)
- Modify: Update index.html to show correct base path

**Step 1: Create files**

```bash
touch CNAME .nojekyll
git add CNAME .nojekyll
git commit -m "chore: GitHub Pages setup files"
```

---

### Task 11: Test Locally

**Step 1: Serve locally**

```bash
cd /Users/Privacy/Documents/projects/portfolio-site
python3 -m http.server 8000
# Open http://localhost:8000
```

**Step 2: Test all pages and interactions**
- Verify all config files load
- Check Y2K styling
- Test navigation
- Verify responsive (if applicable)

**Step 3: Commit if changes needed**

---

## Phase 4: Deployment Prep

### Task 12: GitHub Repository Setup Instructions

**Step 1: Document setup process**

```markdown
## GitHub Pages Setup

1. Create repo: `https://github.com/P4v3r/p4v3r.github.io`
2. Push code
3. Settings > Pages > Source: main branch
4. Wait 2-5 minutes for deployment
5. Site available at: https://p4v3r.github.io
```

**Step 2: Final commit**

```bash
git add README.md
git commit -m "docs: add GitHub Pages setup instructions"
```

---

## Task Checklist Summary

- [ ] Task 1: Config files structure
- [ ] Task 2: CSS Y2K theme
- [ ] Task 3: index.html
- [ ] Task 4: main.js
- [ ] Task 5: projects.html
- [ ] Task 6: about.html
- [ ] Task 7: watching.html
- [ ] Task 8: favorites.html
- [ ] Task 9: blog.html + posts
- [ ] Task 10: CNAME + .nojekyll
- [ ] Task 11: Test locally
- [ ] Task 12: GitHub instructions

---

**Plan complete. Two execution options:**

**1. Subagent-Driven (this session)** - I dispatch fresh subagent per task, review between tasks, fast iteration

**2. Parallel Session (separate)** - Open new session with executing-plans, batch execution with checkpoints

**Which approach?**
