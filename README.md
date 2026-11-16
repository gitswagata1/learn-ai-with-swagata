<div align="center">

# Learn AI with Swagata

A free, self-paced **2-hour course** that takes you from zero to genuinely capable with AI.
One page, no dependencies, no sign-up.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Dependencies](https://img.shields.io/badge/dependencies-none-success)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

## Table of contents

- [What you will learn](#what-you-will-learn)
- [Run it locally](#run-it-locally)
- [Project structure](#project-structure)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## What you will learn

The course is split into **10 modules**:

| # | Module |
| - | ------ |
| 1 | How AI actually works |
| 2 | The landscape and which tool to use |
| 3 | Prompting mastery |
| 4 | The prompt patterns library |
| 5 | Power features beyond chat |
| 6 | Real-world workflows |
| 7 | Build it: your capstone |
| 8 | Agents and automation |
| 9 | Safety, ethics and truth |
| 10 | Your 7-day roadmap |

It ends with a resources and takeaways section so you know what to do next.

## Run it locally

The whole course is a single static page, so there is nothing to install.

```bash
git clone https://github.com/gitswagata1/learn-ai-with-swagata.git
cd learn-ai-with-swagata
npm start            # serves http://localhost:8000 (uses python3 -m http.server)
```

You can also just open `index.html` in a browser.

## Project structure

```
learn-ai-with-swagata/
├── index.html            The complete course (HTML, CSS and JavaScript)
├── index.original.html   Earlier version kept for reference
├── package.json          `npm start` helper
├── .github/              CI, issue templates and workflows
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── LICENSE
└── README.md
```

## Deployment

It is a plain static site and works on any static host. For GitHub Pages, enable Pages
for the `main` branch root; the included `.nojekyll` file makes sure files are served as-is.

## Contributing

Corrections and improvements are welcome. Open an issue using the templates in
`.github/ISSUE_TEMPLATE`, or send a pull request.

## License

Released under the [MIT License](LICENSE).

---

Built by **Swagata Banerjee** · [GitHub](https://github.com/gitswagata1)
