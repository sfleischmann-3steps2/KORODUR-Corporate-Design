# KORODUR Corporate Design – Landing Pages & Styleguide

Einheitliches Design-System für alle KORODUR-Landingpages. Basierend auf dem Entwurf eines externen Designers, erweitert und konsolidiert.

## Live-Vorschau (GitHub Pages)

> **https://sfleischmann-3steps2.github.io/KORODUR-Corporate-Design/**

| Seite | Link | Beschreibung |
|-------|------|-------------|
| Übersicht | [index.html](https://sfleischmann-3steps2.github.io/KORODUR-Corporate-Design/) | Hub-Seite mit Navigation zu allen Seiten |
| ARM | [arm.html](https://sfleischmann-3steps2.github.io/KORODUR-Corporate-Design/arm.html) | Rapid Set ASPHALT REPAIR MIX – Landing Page |
| MICROTOP | [microtop.html](https://sfleischmann-3steps2.github.io/KORODUR-Corporate-Design/microtop.html) | MICROTOP TW Trinkwasserbehälter – Landing Page |
| Styleguide | [styleguide.html](https://sfleischmann-3steps2.github.io/KORODUR-Corporate-Design/styleguide.html) | Living Styleguide v2.0 – Design-Dokumentation |

## Design-System

| Element | Wert |
|---------|------|
| Primärfarbe | Navy `#002d59` (Pantone 295 C) |
| Akzentfarbe | Cyan `#009ee3` |
| Schrift | Gabarito (400, 700, 800, 900) + Arial Fallback |
| Card-Radius | `14px` |
| Button-Radius | `6px` |
| Container | `1320px` max-width |
| Breakpoints | 1100px / 768px / 480px |

## Dateien

```
index.html          -- Hub-Seite / Übersicht
arm.html            -- Landing Page: Rapid Set ASPHALT REPAIR MIX
microtop.html       -- Landing Page: MICROTOP TW Trinkwasserbehälter
styleguide.html     -- Living Styleguide v2.0 (11 Sektionen)
tokens.css          -- Shared Design-Tokens
wireframe.pdf       -- Designer-Wireframe (Referenz)
assets/             -- Logo, Produktbilder, Berater-Fotos
  berater/          -- Berater-Portraitfotos
```

## Referenzdokumente

- `CD Manual KORODUR 310725.pdf` – Corporate Design Manual
- `KORODUR_MasterNEU.potx.pptx` – Master PowerPoint

## GitHub Pages aktivieren

1. Repository Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: **master** / Ordner: **/ (root)**
4. Save → Live nach ca. 1–2 Min.

## Lokale Vorschau

```bash
npx serve .
```
