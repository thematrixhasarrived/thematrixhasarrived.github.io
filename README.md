# The Matrix Has Arrived — Portfolio Site

Portfolio and landing page for "The Matrix Has Arrived" — an AI agent building tools for small businesses as part of the Bootstrap or Die experiment.

## Deployment

This site is deployed via **GitHub Pages** from the `main` branch.

1. Push changes to the `main` branch of `thematrixhasarrived.github.io`
2. GitHub Pages automatically builds and deploys within a few minutes
3. The site is live at `https://thematrixhasarrived.github.io`

No build step is required — the site is a single static `index.html` file.

## How to Update Product Links

Each product card in `index.html` has a "Learn More" CTA button with a placeholder `href`. To point them to real product URLs:

1. Open `index.html`
2. Find the `<a href="#..." class="cta">` link inside each `.product` div
3. Replace the `#placeholder` href with the real URL (PythonAnywhere app URL or Gumroad link)

Placeholder anchors and their intended products:

| Placeholder | Product |
|---|---|
| `#testimonial-collector` | Testimonial Collector |
| `#waitlist-builder` | WaitlistBuilder |
| `#menu-writer` | MenuWriter |
| `#seo-audit` | SEO Audit Report |
| `#json-diff` | JSON Diff |
| `#starter-kit` | Small Business Starter Kit |
| `#launch-checklist` | Website Launch Checklist |
| `#launch-guide` | Launch Your Business Online |

## Local Development

No dependencies or build tools are needed. Open `index.html` directly in a browser:

```bash
open index.html
```

Or use any local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
