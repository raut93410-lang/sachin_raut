# Sachin — Portfolio Website

A clean, professional personal portfolio built with pure HTML, CSS, and JavaScript. No frameworks or build tools required — works directly on GitHub Pages.

---

## 🚀 How to Host on GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click **New repository**
3. Name it exactly: `your-username.github.io`
   - Example: if your username is `sachin123`, name it `sachin123.github.io`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload Your Files
1. In your new repository, click **Add file → Upload files**
2. Upload all 3 files:
   - `index.html`
   - `style.css`
   - `script.js`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repository **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source**, select `Deploy from a branch`
4. Select branch: `main` and folder: `/ (root)`
5. Click **Save**

### Step 4 — Your site is live! 🎉
After 1–2 minutes, visit:
```
https://your-username.github.io
```

---

## ✏️ Customizing Your Portfolio

### Personal Info
Open `index.html` and update:
- **Email** — search for `sachin@example.com`
- **GitHub link** — search for `github.com/sachin`
- **LinkedIn link** — search for `linkedin.com/in/sachin`
- **Resume button** — in `script.js`, replace the alert with `window.open('your-resume-url.pdf')`

### Projects
Find the `<!-- PROJECTS -->` section in `index.html`. Each project card looks like:
```html
<div class="project-card reveal delay-1">
  <div class="project-img" style="background: linear-gradient(...)">
    <div class="project-overlay"><div class="project-icon">⚡</div></div>
  </div>
  <div class="project-info">
    <div class="project-tags"><span>React</span>...</div>
    <h3>Project Name</h3>
    <p>Description here.</p>
    <div class="project-links">
      <a href="YOUR_LIVE_LINK" class="link-demo">Live Demo ↗</a>
      <a href="YOUR_GITHUB_LINK" class="link-code">GitHub ↗</a>
    </div>
  </div>
</div>
```

### Skills
Find the `<!-- SKILLS -->` section. Adjust `data-level="85"` (0–100) for each skill bar.

### Colors
In `style.css`, edit the `:root` variables at the top:
```css
--accent: #c8a96e;     /* gold accent color */
--ink: #1a1814;        /* main text color */
--bg: #f8f6f1;         /* background color */
```

### Contact Form
The form currently simulates a send. To make it actually send emails, sign up at [formspree.io](https://formspree.io) and replace the `setTimeout` in `script.js` with a real fetch call to your Formspree endpoint.

---

## 📁 File Structure
```
portfolio/
├── index.html    ← Main HTML structure
├── style.css     ← All styling
├── script.js     ← Animations & interactions
└── README.md     ← This file
```

---

Built with ♥ — No frameworks, no dependencies, just clean HTML/CSS/JS.
