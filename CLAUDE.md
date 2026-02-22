# Gus Greenstein – Website Project

## What this is
An academic personal website hosted on GitHub Pages, replacing a previous Weebly site.
- **Live URL:** https://gusgreenstein.com (custom domain, DNS pointed from Weebly/Register.com)
- **GitHub repo:** https://github.com/gusgreenstein/gusgreenstein.github.io
- **Local files:** /Users/gusgreenstein/Desktop/gusgreenstein.github.io/

## How to push changes to GitHub
The repo uses SSH authentication. After editing any file, run:
```
cd "/Users/gusgreenstein/Desktop/gusgreenstein.github.io"
git add .
git commit -m "description of changes"
git push origin main
```
No token or password needed — SSH keys are set up on this machine.

## Site structure
- `index.html` — About page (photo, bio, contact links)
- `research.html` — Research page (publications, working papers, etc.)
- `profile_pic.jpg` — Headshot photo
- `CV.pdf` — Current CV
- `fonts/` — Self-hosted PT Sans font files (Regular, Bold, Italic)
- `CNAME` — Sets custom domain to gusgreenstein.com

## Design
- Font: PT Sans (self-hosted in fonts/ folder)
- Color: #2a2a2a (dark gray)
- Max content width: 720px
- Two pages: About and Research, linked via nav bar

## About page (index.html)
- Layout: photo on left (320px wide), name + title + contact links on right
- Title lines: Assistant Professor / Institute of Public Administration / Faculty of Governance and Global Affairs / Leiden University
- Contact links: Email (g.h.greenstein@fgga.leidenuniv.nl), CV, Twitter (@gusgreenstein), LinkedIn (linkedin.com/in/gusgreenstein/)

## Research page (research.html)
- Each publication is a single inline paragraph: "Author(s). Year. [Linked Title]. *Journal* details."
- Sections: Journal Articles, Book Chapters, Working Papers, In Progress, Selected Policy Reports and Other Writing
- PDFs hosted in root of repo: greenstein-2022-world-bank-safeguards.pdf, greenstein-hledik-2016-demand-charges.pdf, greenstein-honig-2024-managing-aid-personnel.pdf, wbg-global-footprint.pdf

## Domain situation
- Domain gusgreenstein.com is registered through Weebly/Register.com (~$30/yr)
- DNS A records updated to point to GitHub Pages IPs
- Plan to transfer domain to Namecheap (~$10-12/yr) once DNS transition is confirmed working
