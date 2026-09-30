<div align=”center”>

# Learn AI with Swagata

**A free, self-paced 2-hour AI course — from zero to genuinely capable.**

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-Free-brightgreen?style=flat-square)
![Modules](https://img.shields.io/badge/Modules-10-A855F7?style=flat-square)

[**Live Demo**](https://understand-ai-with-swagata-banerjee.netlify.app/) · [**Curriculum**](#-curriculum) · [**Run Locally**](#-run-it-locally)

</div>

---

Takes complete beginners from *”I’ve never used it”* to building real AI workflows — understanding how it works, mastering prompting, unlocking power features, and thinking about safety.

Single self-contained `index.html`. No build step, no dependencies, no backend. Just open it in a browser.

---

## ✨ Features

- **Real multi-page app** — Home, Curriculum, Lessons, and Resources, powered by a lightweight hash router (shareable deep links like `#/lesson/3`).
- **10-module curriculum across 4 parts** — Foundations → Core Skill → Power & Practice → Frontier & Trust.
- **Saved progress** — completed modules, quiz answers, checklists, theme, and “continue where you left off” all persist in the browser via `localStorage`.
- **Interactive elements** — a live prompt builder, knowledge-check quizzes, completion checklists, and a completion modal.
- **Typewriter hero**, **dark mode**, and a **progress ring/bar**.
- **Fully responsive** — QA-tested with no horizontal overflow from 320px phones up to 1280px desktops, in both light and dark mode.
- **Accessible** — `aria-label`s, reduced-motion support, keyboard-friendly navigation.

---

## 📚 Curriculum

| # | Module | Part |
|---|--------|------|
| 1 | How AI actually works | Foundations |
| 2 | The landscape & which tool to use | Foundations |
| 3 | Prompting mastery | The core skill |
| 4 | The prompt patterns library | The core skill |
| 5 | Power features beyond chat | Power & practice |
| 6 | Real-world workflows | Power & practice |
| 7 | Build it — your capstone | Power & practice |
| 8 | Agents & automation | Frontier & trust |
| 9 | Safety, ethics & truth | Frontier & trust |
| 10 | Your 7-day roadmap | Frontier & trust |

Plus a **Resources** page with a printable cheat sheet, a plain-English glossary, and an FAQ.

---

## 🚀 Run it locally

No tooling required — just open the file:

```bash
open index.html        # macOS
# or double-click index.html in your file manager
```

Or serve it (recommended, so the router works cleanly):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## 🌐 Deploy

It’s a static site, so it works on any static host.

- **Netlify Drop** — drag the project folder onto [app.netlify.com/drop](https://app.netlify.com/drop).
- **GitHub Pages** — enable Pages on this repo (`main` branch, root). `.nojekyll` is already included so files serve as-is.
- **Vercel / Cloudflare Pages / Surge** — point them at the repo or folder.

---

## 🛠️ Tech

- **Plain HTML, CSS, and vanilla JavaScript** in a single file — zero dependencies.
- Theming via CSS custom properties (light/dark).
- Client-side hash routing and `localStorage` for state.

---

## 📁 Structure

```
.
├── index.html        # the entire site
├── .nojekyll         # tells GitHub Pages to serve files as-is
├── .gitignore
└── README.md
```

---

## 📄 License

Free to use and adapt for teaching. © Swagata Banerjee.
