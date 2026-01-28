# BPG Elevside - Test

> **[Se Live Demo](https://metis-utdanning.github.io/test-bpg-elevside_via_github/)**

Test landing page for elever - kan embeddes i Teams og Squarespace.

---

## Funksjoner

- Nyheter fra RSS-feed (bergenprivategymnas.no)
- Snarveier til InSchool, Elevsiden, OneDrive, IT-hjelp
- Teams SDK-integrasjon for embedding
- **Tema-bytte** via [Metis Design System](https://github.com/Metis-Utdanning/metis-design_system)

## Tema-testing

Siden har en tema-velger øverst til høyre for å teste alle Metis-temaer:

| Tema | Primærfarge |
|------|-------------|
| BPG | #1F4739 (grønn) |
| Metis VGS | #EE2737 (rød) |
| Privatist | #00b398 (teal) |
| Privatlærer | #FF8000 (oransje) |
| Metis | #188AAD (cyan-blå) |

## Teknologi

- Vanilla HTML/CSS/JS
- [Metis Design System](https://github.com/Metis-Utdanning/metis-design_system) for theming
- Microsoft Teams SDK for embedding
- CORS proxy for RSS-feed

## Bruk i andre prosjekter

```html
<!-- Legg til Metis Design System -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Metis-Utdanning/metis-design_system@main/dist/themes/bpg.css">

<!-- Eller bruk loader for dynamisk tema -->
<script src="https://cdn.jsdelivr.net/gh/Metis-Utdanning/metis-design_system@main/dist/loader.js"
        data-theme="bpg"></script>
```

## Relaterte prosjekter

| Repo | Beskrivelse |
|------|-------------|
| [metis-design_system](https://github.com/Metis-Utdanning/metis-design_system) | CSS Design System |
| [MetisDB](https://github.com/Metis-Utdanning/MetisDB) | Sentral database |
