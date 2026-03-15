# Urs Consulting — Portfolio Site

Professional portfolio site for Urs Consulting — help center strategy, content architecture, and AI readiness consulting.

**Live at:** [https://urswulf.com](https://urswulf.com)

## Tech Stack

- Static HTML / CSS / vanilla JS
- Hosted on GitHub Pages
- Contact form via [Formspree](https://formspree.io)

## Local Development

Open `index.html` in a browser. No build step required.

## Deployment

This site is deployed automatically via GitHub Pages from the `main` branch. Push changes and they'll be live within minutes.

## Structure

```
├── index.html                         — Main single-page site
├── styles.css                         — All styling
├── CNAME                              — Custom domain config
├── examples/
│   ├── content-architecture.html      — Content architecture example
│   ├── product-launch-docs.html       — Product launch docs example
│   └── audit-ai-readiness.html        — Audit & AI readiness example
└── assets/                            — Images, favicon, etc.
```

## Setup Notes

1. **Contact form:** Replace `YOUR_FORMSPREE_ID` in `index.html` with your Formspree form ID. Create a free account at [formspree.io](https://formspree.io).
2. **Custom domain:** The `CNAME` file is set to `urswulf.com`. Configure your domain registrar's DNS to point to GitHub Pages ([docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)).
