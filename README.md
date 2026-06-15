# Charles Joshua P. Dela Austria — Personal Website

A multi-page personal website built from Charles's resume, using the provided
lavender/cream color palette and a light/dark theme toggle.

## How to view

Just open `index.html` in any modern browser. No build step required.

```bash
# Optional: serve locally to test (prevents any CORS issues)
python -m http.server 8000
# then visit http://localhost:8000
```

## File tree (one file/folder per section)

```
website/
├── index.html              ← Home (hero, highlights, pillars)
├── about.html              ← About (story, pillars, tools)
├── portfolio.html          ← Portfolio (projects, experience, achievements)
├── certificates.html       ← Certificates & Education
├── services.html           ← Services & Pricing
├── contact.html            ← Contact (Calendly→Zoom, form, socials)
│
├── css/
│   ├── style.css           ← Shared: palette variables, theme, layout
│   ├── home.css            ← Home page styles
│   └── pages.css           ← Inner page styles
│
├── js/
│   └── main.js             ← Dark mode toggle, mobile nav, scroll reveal
│
├── data/
│   ├── profile.json        ← Name, role, summary, contact
│   ├── about.json          ← Pillars + tools
│   ├── services.json       ← Services + pricing
│   ├── portfolio.json      ← Experience + achievements
│   └── certificates.json   ← Certifications + education
│
├── assets/                 ← (images / icons go here)
└── README.md
```

## Color palette (from the provided image)

| Token | Hex | Use |
|-------|-----|-----|
| Cream | `#EEE0CB` | Light background |
| Lavender | `#D9D1D9` | Surface / borders |
| Periwinkle | `#C4C2E5` | Accent soft |
| Lavender deep | `#B0B2EF` | Accent |
| Lavender blue | `#9DA1F9` | Primary accent |

Dark mode uses deep indigo backgrounds derived from the same palette.

## Features

- ✅ 6 sections (Home, About, Portfolio, Certificates, Services, Contact)
- ✅ Light / Dark mode toggle (remembered via `localStorage`)
- ✅ Fully responsive (mobile hamburger menu)
- ✅ Scroll-reveal animations
- ✅ Calendly widget placeholder (integrates to Zoom once linked)
- ✅ Contact form + social media links
