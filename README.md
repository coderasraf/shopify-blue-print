# Shopify Elite Handbook

A personal, self-contained career handbook for becoming an elite Shopify App Developer, Shopify Plus Engineer, Solutions Architect and Upwork Top-Rated freelancer.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Open-2EA44F?logo=githubpages&logoColor=white)](https://coderasraf.github.io/shopify-blue-print/) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Shopify](https://img.shields.io/badge/Shopify-7AB55C?logo=shopify&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=white)

## Overview

The whole handbook lives in a single `index.html` file: content, styles and the small reading app around it. It is organized as a sidebar of topic groups, each with in-depth sections, code samples and diagrams, plus tools for tracking progress and taking notes while studying.

## Features

- Curriculum grouped into: Start Here, Shopify App Foundations, Shopify APIs, Extensibility (Functions & Extensions), Plus & Headless Commerce, Backend Engineering, Frontend Engineering, AI Engineering for Commerce, Automation & No-Code, Systems Integration, Upwork & Freelance Mastery, a 100+ project library and a 12-month roadmap
- Topics include embedded apps and App Bridge, Shopify CLI, OAuth and token exchange, webhooks, Billing API, GraphQL cost model and bulk operations, Storefront and Customer Account APIs, Shopify Functions, Checkout UI extensions, Hydrogen/Oxygen, Prisma + PostgreSQL, Redis, Docker, CI/CD, Remix, OpenAI/Anthropic APIs, n8n, ERP/CRM integrations, pricing and proposals
- Full-text search across sections
- Per-section completion checkboxes with an overall progress bar
- Bookmarks and a personal notes panel (with download), all saved to `localStorage`
- Syntax-highlighted code samples (Prism) with copy buttons, and Mermaid diagrams
- Light/dark theme toggle and print / save-as-PDF
- Keyboard shortcuts: `/` search, `t` theme, `n` notes, `m` sidebar, `b` bookmarks, `p` print, `j`/`k` next/previous section, `?` help, `Esc` close

## Tech Stack

- HTML5, CSS3 and vanilla JavaScript (single file)
- [Prism.js](https://prismjs.com/) 1.29 (via cdnjs) for code highlighting
- [Mermaid](https://mermaid.js.org/) 10 (via jsDelivr) for diagrams
- Google Fonts (Inter, JetBrains Mono)
- GitHub Pages (Jekyll Pages workflow) for hosting

## Getting Started

No build step is needed.

```bash
git clone https://github.com/coderasraf/shopify-blue-print.git
cd shopify-blue-print
# open index.html in your browser, or serve it locally:
npx serve .
```

## Project Structure

```text
shopify-blue-print/
├── index.html                              # The entire handbook (content, styles, scripts)
└── .github/workflows/jekyll-gh-pages.yml   # Deploys to GitHub Pages on push to main
```

## Live Demo

[coderasraf.github.io/shopify-blue-print](https://coderasraf.github.io/shopify-blue-print/)

## Author

Built by **Ashraf Siddik**, Shopify developer & CRO specialist.

- Website: [ashraf-siddik.com](https://ashraf-siddik.com)
- GitHub: [@coderasraf](https://github.com/coderasraf)
