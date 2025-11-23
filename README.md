# Mutorium Labs – Website

This is the codebase for the **Mutorium Labs** website – a small content site
focused on mutation testing for Web3 and zero-knowledge systems.

The site is built with the **Astro blog starter** and customized with:

- Dark/light theme toggle (respects system preference by default)
- MDX support for rich blog posts (code blocks, headings, etc.)
- A simple, responsive layout inspired by RareSkills’ ZK Book
- Blog section for articles, notes, and research updates

Deployed via **Vercel** from the `main` branch.

---

## 🧱 Tech stack

- [Astro](https://astro.build/) – static site generator
- Markdown + MDX – blog content
- Vanilla CSS – in `src/styles/global.css`
- Vercel – hosting & automatic deployments on push

---

## 🚀 Project structure

Only the parts that matter for this site:

```text
├── public/
│   ├── favicon.svg
│   └── robots.txt        # optional
├── src/
│   ├── assets/           # images used in posts / layout
│   ├── components/       # Header, Footer, ThemeToggle, etc.
│   ├── content/
│   │   └── blog/         # markdown / mdx blog posts
│   ├── layouts/
│   │   └── BlogPost.astro
│   └── pages/
│       ├── index.astro   # landing page
│       ├── about.astro
│       └── blog/
│           └── index.astro
├── astro.config.mjs
├── package.json
└── README.md
