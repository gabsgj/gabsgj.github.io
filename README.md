# gabsgj.github.io

> Minimal, cinematic "coming soon" site for Gabriel James — live at [gabrieljames.me](https://gabrieljames.me).

## Overview

This repo powers the public holding page for Gabriel's forthcoming portfolio + studio. It leans on a single handcrafted `index.html` with beautiful typography, particle effects, and a roadmap that keeps visitors informed while the full site ships.

## Highlights

- **Hero story** with animated typewriter headline, stat cards, and direct CTA to book a build sprint.
- **Glassmorphism contact card** highlighting current focus areas and office hours.
- **Roadmap panels** outlining upcoming builds, expectations, and availability.
- **Lightweight particles + accessibility** (respects `prefers-reduced-motion`).
- **Zero dependencies** — just HTML/CSS/JS for instant deploys.

## Local development

```powershell
# clone + navigate
git clone https://github.com/gabsgj/gabsgj.github.io.git
cd gabsgj.github.io

# open the page locally
start index.html
```

For live reload you can optionally run a tiny static server (e.g. `npx serve .`) but it's not required.

## Deployment

- The site is published through GitHub Pages and pointed to **gabrieljames.me** via the `CNAME` file.
- Any push to `main` redeploys automatically. Keep assets lightweight for fast Time-To-First-Paint.

## Contact

Questions or collaboration ideas? Email [gabriel22dec@gmail.com](mailto:gabriel22dec@gmail.com).