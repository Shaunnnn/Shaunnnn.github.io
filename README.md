# Shaun Yim — Portfolio

My personal portfolio site, built as a single-page site covering my background, work experience, projects, and skills.

**Live site:** https://shaunnnn.github.io

## About

IT professional building cloud-integrated, automation-driven, and AI-assisted applications — currently reading Computer Science at the University of London (Goldsmiths) while shipping production-style systems on the side.

## What's on the site

- **Home** — quick intro and featured projects
- **About** — background, education, and certifications
- **Experience** — work history, including Mirae Distribution Pte Ltd and Fujitsu Asia
- **Projects** — LOOP'd (e-commerce platform with a custom PayNow QR payment integration), a GPT-powered Nutrition Chatbot built at the SIM-UOL CSSC Hackathon, and Pocket Storehouse (final year project)
- **Skills** — grouped by languages, cloud & backend, AI & automation, security & networking, and tools
- **Contact** — email and phone, one click to copy

## Built with

Plain HTML, CSS, and JavaScript — no framework or build step. Light/dark theme support, keyboard navigation (press 1–6 to jump between pages), and a lightbox for project screenshots.

## Structure

```
index.html      → the whole site
images/         → project screenshots used on the Projects page
```

## Running locally

No build step needed — just open `index.html` in a browser, or serve the folder with any static file server, e.g.:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
