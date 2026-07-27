# JABAL · High Quality Water

A premium, bilingual (English / العربية) single-page site for **JABAL High Quality Water** — a reimagining of jabalwater.com.

Build-free: everything runs by opening `index.html`. No bundler, no dependencies to install.

## Features
- **Immersive "descent through water" design** — dark editorial theme with an animated underwater backdrop and the original water-splash effect showing through the content.
- **Live 3D bottle** — the real product model (glTF), with cinematic camera (zoom + orbit), drag-to-spin, and a wrapped brand label. Lazy-loaded with a progress spinner; falls back gracefully.
- **Interactive WebGL** — click anywhere for a water splash (ripples, foam, droplets).
- **Reflective coverflow carousel** — real promo posters as gently-swaying water drops.
- **Full shop** — real products/prices (EGP), filters, and a working cart.
- **Bilingual AR ⇄ EN** with full RTL support.
- **SEO-ready** — meta, Open Graph, Twitter cards, JSON-LD (Organization + Products), `robots.txt`, `sitemap.xml`, favicons, and a web manifest.

## Structure
```
index.html            # the whole site (HTML + CSS + JS)
assets/               # model.glb, images, water-splash.html, fonts (three.min.js), favicons, og-image
robots.txt · sitemap.xml · site.webmanifest
```

## Deploy (any static host)
It's a static site — drop the folder on any static host:
- **GitHub Pages:** push this repo, then Settings → Pages → deploy from `main` / root.
- **Netlify / Vercel / Cloudflare Pages:** point at the repo, no build command, publish directory = repo root.

## Before going live
The absolute URLs (canonical, Open Graph, sitemap, structured data) assume the domain **https://jabalwater.com/**. If you deploy elsewhere, update those references. Add real social profile URLs (footer + JSON-LD `sameAs`) when available.

---
Contact: **info@jabalwater.com** · **011 1955 9955**
