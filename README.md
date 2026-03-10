# Corridor Corporate Design – Designfindung

3 gestalterisch unterschiedliche Landing-Page-Varianten mit identischem Inhalt (ARM Landing Page) als Entscheidungsgrundlage fuer das KORODUR Corporate Design.

## CD-Grundlagen (fix)

| Element | Wert |
|---------|------|
| Primaerfarbe | Navy `#002d59` (Pantone 295 C) |
| Akzentfarbe | Cyan `#009ee3` |
| Grautoene | `#ececed` (hell), `#d9dada` (mittel) |
| Schrift | Gabarito (400, 700, 800, 900) + Arial Fallback |
| Logo | Nur Farbvariante, nur auf Weiss |
| Ton | B2B, technisch-praezise, professionell |

## Die 3 Varianten

### Variante A: Bold & Editorial
Magazin-Stil mit Vollbild-Hero, dramatischer Typografie (H1 bis 5rem), horizontalen Karussells, dunklen Sektionsinversionen und Floating CTA.

### Variante B: Clean & Strukturiert
Maximale Klarheit mit Split-Hero, kompakter Typografie (H1 max 2.6rem), vertikaler Timeline, gefilterten Grids, Scroll-Fortschrittsbalken und Inline-Formular.

### Variante C: Modern & Dynamisch
Premium-Tech-Aesthetik mit animiertem Gradient-Hero, Glasmorphismus, Scroll-Animationen, Masonry-Grid, Bottom-Sheet-Interaktionen und animiertem Trust-Marquee.

## Vergleichsmatrix

| Element | A: Editorial | B: Strukturiert | C: Dynamisch |
|---------|-------------|-----------------|--------------|
| Hero | Vollbild-Overlay | Split Text/Bild | Animierter Gradient |
| H1 max | 5rem | 2.6rem | 3.5rem |
| Container | Full-Bleed | 1100px | 1200px + Breakouts |
| Dunkle Sektionen | Problem + Zielgruppen | Keine extra | Technik + Berater |
| Karten-Stil | Minimal, Weissraum | Duenner Shadow + Border | Glasmorphismus |
| Schritte | Horiz. Karussell | Vertikale Timeline | Icon-Kreise + Pfeile |
| Referenzen | Horiz. Karussell | Gefiltertes Grid | Masonry |
| Scroll-Effekte | Header-Transition | Fortschrittsbalken | Volle Reveal-Animationen |
| CTA-Muster | Floating Sticky CTA | Inline Formular | Zentrierter Single CTA |

## Dateien

```
tokens.css                        -- Geteilte Design-Tokens
assets/                           -- Logo, ARM-Bilder, Berater-Fotos
variante-a-editorial.html         -- Bold & Editorial
variante-b-strukturiert.html      -- Clean & Strukturiert
variante-c-dynamisch.html         -- Modern & Dynamisch
```

## Lokale Vorschau

Dateien direkt im Browser oeffnen oder mit einem lokalen Server:

```bash
npx serve .
```
