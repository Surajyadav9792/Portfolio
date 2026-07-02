# Suraj Yadav — Developer Portfolio

A personal portfolio website showcasing my full-stack (MERN) projects, skills, and
AI/GenAI work. Built on the Colorlib "ftco" portfolio template (HTML, CSS,
JavaScript, Bootstrap) with a custom dark theme.

**Live site:** _add your URL after deploying_

---

## Tech
HTML5 · CSS3 · JavaScript · Bootstrap 4 · jQuery · AOS / Owl Carousel animations

## Featured projects
1. **CodeJudge** — Online coding judge (React, Node.js, Express, MongoDB, JWT, Judge0)
2. **AgenticForge** — Multi-agent AI software-engineering platform (LangGraph, Gemini, Redis, Docker, React, WebSockets)
3. **Swiggy Clone** — Food-ordering UI (React, Redux Toolkit, Tailwind CSS)

---

## Run locally
This is a static site — no build step.

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
# open index.html in a browser, or serve it:
python3 -m http.server 5500
# then visit http://localhost:5500
```

## Files you must add before publishing
- `images/profile.png` — replace the placeholder with your own photo (portrait ~800×1000 or square; face centred)
- `images/proj_codejudge.png`, `images/proj_agenticforge.png`, `images/proj_swiggy.png` — replace with real screenshots when ready
- `Suraj_Yadav_Resume.pdf` — drop your resume PDF in the repo root (the "Download CV / Resume" buttons link to it)
- Update the **LeetCode** link in `index.html` (search for `your-username`)

---

## Deployment

### Option A — GitHub Pages
1. Push this repo to GitHub (repo can be named anything; for a user site use `<username>.github.io`).
2. Repo **Settings → Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**, **Branch: `main`**, **Folder: `/ (root)`**, then **Save**.
4. Your site goes live at `https://<username>.github.io/<repo>/` within a minute or two.

### Option B — Vercel
1. Go to vercel.com → **Add New → Project** → import this GitHub repo.
2. Framework preset: **Other**. Leave build command empty; **Output directory: `.`** (root).
3. **Deploy** → you get a `https://<project>.vercel.app` URL (custom domains supported).

---

_Template: [Colorlib](https://colorlib.com) (CC BY 3.0). The Colorlib credit in the footer is required by the license._
