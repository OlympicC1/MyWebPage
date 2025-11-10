# DudeEngine

DudeEngine * curated, photo-first static site presenting "Dude: My Service Animal"

Live
- Demo: https://smithsoni3n.github.io/DudeEngine/  
- Status: Website launched — final site is live

────────────────────────────────────────────────────────
PROJECT SUMMARY
────────────────────────────────────────────────────────


My purpose for DudeEngine is simple: put Dude front‑and‑center with big, honest photography,
a stripped‑down narrative, and clear care & safety notes you can scan in one pass.
This lean, photo‑first microsite strips the fluff so reviewers,
caretakers, and visitors get the story and core facts in seconds.
Built without a build pipeline so edits, image swaps, and deploys stay fast and low‑risk.


────────────────────────────────────────────────────────
HIGHLIGHTS
────────────────────────────────────────────────────────
- Single-file UX: Story & Facts live in one HTML file with a tiny show/hide script for simple navigation.
- Photo-first aesthetic with a grounded, earth-tone palette.
- No heavy tooling: Tailwind utilities are used via CDN — quick to author and maintain.
- Mobile-friendly and semantically structured for accessibility.
- Tight, portable layout good for portfolio listings or lightweight demos.

────────────────────────────────────────────────────────
QUICK START (open locally)
────────────────────────────────────────────────────────
```bash
git clone https://github.com/OlympicC1/DudeEngine.git
cd DudeEngine/docs
# then open index.html in your browser
```

────────────────────────────────────────────────────────
FILE STRUCTURE
────────────────────────────────────────────────────────
docs/ 
- index.html       — main page (Story & Facts content handled in one file using show/hide)
- styles.css       — custom styles and color variables (site design system)
- Flowers.jpg.jpg  — photograph used in the Story section
- stick.jpg        — photograph used in the Facts section

(top-level)
- docs/            — site contents and published assets 

──────────────────────────────────────────────────────── 
PROJECT ROLE & RESPONSIBILITIES
──────────────────────────────────────────────────────── 

> **Author / Maintainer: Crystal Reise**
>
> - Authored all site copy and structured the HTML for semantic clarity.  
> - Designed and implemented the stylesheet system (styles.css + Tailwind utilities) for a cohesive, photo-first look.  
> - Built a lightweight show/hide UX to surface Story & Facts with minimal code.  
> - Curated, optimized, and placed photography to lead the visual narrative.  
> - Managed deployment and previews via GitHub Pages (docs/ publishing) and local/VDS workflows.
>
> **Outcome**
>
> - A lean, editable microsite — portfolio-ready, visually coherent, and simple to update for quick reviewer evaluation.


────────────────────────────────────────────────────────
TOOLS & TECHNOLOGIES
────────────────────────────────────────────────────────
- HTML5 — semantic structure and content
- CSS — custom stylesheet (styles.css) with variables and layout
- Tailwind CSS (CDN) — utility classes for markup convenience
- GitHub Pages — static hosting / deployments (docs/)
- Browser — previewing and QA
- Image assets — Photographs of Dude by OlympicC1. Do not reuse or redistribute without permission.
- VDS - (Virtual Dedicated Server) — remote virtual server used for testing or hosting
- VMware - Workstation Pro 17 — local virtual machine for testing, preview, and isolated builds
- Visual Studio Code — editor used for authoring, quick previews, and local edits
- Python — used to help coding (small helper scripts, quick local servers, and automation)
  
────────────────────────────────────────────────────────
EDITING / MAINTENANCE NOTES
────────────────────────────────────────────────────────
- Update copy: edit docs/index.html  
- Update styles: edit docs/styles.css  
- Replace images: add/replace files in docs/ and update the src paths in index.html  
- Tailwind is provided via CDN — no local build step by default

────────────────────────────────────────────────────────
SOURCE & CONTACT
────────────────────────────────────────────────────────
- Repo: https://github.com/OlympicC1/DudeEngine  
- Live site: https://olympicc1.github.io/DudeEngine/

────────────────────────────────────────────────────────
NOTES
────────────────────────────────────────────────────────
- This README intentionally omits license, contributing, and development workflow sections by request.
- File structure intentionally highlights the docs/ folder first to reflect how the site is published.
