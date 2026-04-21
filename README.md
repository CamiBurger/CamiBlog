# CamiBlog
A blog for Cami's projects

> My personal website — a multi-context home base for whoever wants to know more about me.

**Live domains:** `camis.site` · `camillas.site`

---

## What is this?

This site is built to serve multiple audiences depending on how you know me. Rather than a single-purpose portfolio or blog, it's organized into distinct sections — each one tailored to a different context: professional, automotive, personal, and technical.

The public face of the site is a clean resume and introduction. Behind a private login, there's a lot more.

---

## Project Chapters

The project is broken into phases, each building on the last. Core functionality ships first; private and personal features layer in afterward.

### Chapter 1 — Resume / Professional *(public)*
The foundation of the site. A polished, public-facing resume and professional profile.

- Work history, skills, and experience
- Downloadable resume (PDF)
- Contact or reach-out section
- Designed to hold up in a professional context — shareable with recruiters, colleagues, or collaborators

### Chapter 2 — Private Access Layer *(auth required)*
A login system that gates the rest of the site's content. Keeps the personal stuff personal.

- User sign-in (invite-only or single-user)
- Session management
- Public vs. private route separation
- All chapters below live behind this wall

### Chapter 3 — Cars & Racing *(private)*
A dedicated space for the automotive side of my life.

- Build logs, mods, and project car documentation
- Race events, results, or track day recaps
- Photo/media gallery
- Possibly: specs, lap times, or car-specific pages

### Chapter 4 — Personal Blog *(private)*
A writing space for things that don't fit a professional context.

- Long-form posts and personal reflections
- Categorized by topic or date
- Low-pressure, no-audience writing — just for me (and those I let in)

### Chapter 5 — Tinkering Projects *(private)*
Electronics, computers, and whatever I'm building or breaking.

- Project writeups (hardware, software, embedded systems, etc.)
- Notes, schematics, code snippets
- Work-in-progress logs alongside finished builds

### Chapter 6 — Wishlist *(private)*
A personal wishlist. Simple, useful, and mine.

- Items organized by category or priority
- Shareable link or view-only mode for specific people
- Managed privately — not public-facing

---

## Site Architecture (Planned)

```
camis.site/
├── /                   → Resume (public)
├── /login              → Auth gate
└── /home               → Private landing (post-login)
    ├── /cars           → Cars & Racing
    ├── /blog           → Personal Blog
    ├── /projects       → Tinkering Projects
    └── /wishlist       → Wishlist
```

---

## Tech Stack

> ⚠️ Stack is still being decided. This section will be updated as choices are locked in.

Candidates under consideration:
- **Frontend:** React / Next.js · Vanilla HTML/CSS/JS · Astro
- **Auth:** NextAuth · Clerk · Custom session handling
- **Backend/DB:** Supabase · PlanetScale · SQLite · Firebase
- **Hosting:** Vercel · Cloudflare Pages · Self-hosted VPS

---

## Development Roadmap

| Chapter | Feature | Status |
|---------|---------|--------|
| 1 | Resume / public landing page | 🔲 Not started |
| 2 | Auth / private login | 🔲 Not started |
| 3 | Cars & Racing section | 🔲 Not started |
| 4 | Personal blog | 🔲 Not started |
| 5 | Tinkering projects | 🔲 Not started |
| 6 | Wishlist | 🔲 Not started |

---

## Running Locally

> Setup instructions will be added once the stack is decided.

---

## Notes

- This is a personal project and not open for public contribution
- Private sections are invite-only and not publicly accessible by design
- Domains: `camis.site` and `camillas.site` both point to the same project
