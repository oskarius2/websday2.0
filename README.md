# Websday — websday.se

Premium webbyrå i Stockholm. Den här sajten är byggd med ren HTML/CSS/JS — ingen build-process, inga dependencies, bara ladda upp och kör.

## Struktur

```
websday-site/
├── index.html       ← Hela sajten (allt i en fil)
├── vercel.json      ← Deploy-config för Vercel
├── .gitignore
└── README.md
```

## Deploy på Vercel

1. Pusha repot till GitHub
2. Gå till [vercel.com](https://vercel.com) → Add New Project
3. Importera repot
4. Klicka Deploy — klart

## Koppla eget domännamn (websday.se)

1. I Vercel: Settings → Domains → Add `websday.se`
2. Vercel visar DNS-inställningar (A-record + CNAME)
3. Uppdatera hos din domänregistrator
4. Klart på ~5 min

## Uppdatera sajten

Gör ändringar i `index.html` → commit → push → Vercel deployr automatiskt.

## Byggd med

- HTML5 / CSS3 / Vanilla JS
- Google Fonts (DM Serif Display, Syne, Manrope)
- Canvas API (particle system)
- Scroll-driven parallax (orbs, drifting type, particles)
- Glassmorphism design system

---

Designad & byggd av Websday.
