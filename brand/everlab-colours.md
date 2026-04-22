# Everlab — Colours

Our colours give the brand a strong sense of consistency across all applications.
The palette is neutral, with warm brand tones (creme, orange, red) that feel human
and grounded — not clinical.

---

## Token System

Colours are structured as semantic tokens with two modes: **Light** and **Dark**.
Token naming convention: `2026/{bg or fg}/{category}/{shade}`

- `bg` = background use
- `fg` = foreground / text use

---

## Neutral Tokens

These are the primary base colours used across all layouts and surfaces.

| Token | Light Mode | Dark Mode | Usage |
|---|---|---|---|
| `2026/bg/neutral/100` | `#FFFFFF` (100% opacity) | `#000000` (100% opacity) | Primary background |
| `2026/bg/neutral/200` | `#FFFFFF` (50% opacity) | `#000000` (50% opacity) | Secondary / overlay background |
| `2026/bg/neutral/300` | `#FFFFFF` (30% opacity) | `#000000` (30% opacity) | Subtle background, frosted layers |
| `2026/fg/neutral/100` | `#000000` (100% opacity) | `#FFFFFF` (100% opacity) | Primary text |
| `2026/fg/neutral/200` | `#000000` (60% opacity) | `#FFFFFF` (60% opacity) | Secondary / supporting text |
| `2026/fg/neutral/300` | `#000000` (40% opacity) | `#FFFFFF` (40% opacity) | Placeholder, disabled, captions |

---

## Brand Colour Tokens

### Crème

Crème is the primary brand warmth colour — used for backgrounds, cards, and
warm surface treatments.

| Token | Light Mode | Dark Mode |
|---|---|---|
| `2026/bg/brand/creme/100` | `#F4F4F3` | `#4F4F48` |
| `2026/bg/brand/creme/200` | `#ECE4DC` | `#777570` |
| `2026/fg/brand/creme/100` | `#F4F4F3` | `#4F4F48` |
| `2026/fg/brand/creme/200` | `#ECE4DC` | `#777570` |

### Orange / Red

The brand accent — used for highlights, labels, CTAs, and key brand moments.
Orange is the primary accent; Red is the deeper supporting tone.

| Token | Light Mode | Dark Mode |
|---|---|---|
| `2026/bg/brand/orange/100` | `#F17551` | `#F17551` (same both modes) |
| `2026/fg/brand/red/200` | `#D04926` | `#F17551` |

---

## Colour Colourways (How to Apply)

The brand uses **two colourways** — seen across social, marketing, and editorial:

### Colourway 1 — Light
- Background: `bg/neutral/100` White
- Text: `fg/neutral/100` Black
- Accent: `bg/brand/orange/100` Orange or `fg/brand/red/200` Red

### Colourway 2 — Dark
- Background: `fg/neutral/100` Black (inverted)
- Text: `bg/neutral/100` White (inverted)
- Accent: `bg/brand/orange/100` Orange or `bg/brand/creme/200` Crème

> In social and H2-style layouts, these two colourways are used
> side-by-side for visual rhythm and contrast.

---

## Colour Usage Guide

| Colour | Approx. usage | Primary use |
|---|---|---|
| White / Crème 100 | ~65% | Backgrounds, negative space |
| Black | ~26% | Text, UI, dark backgrounds |
| Neutrals (fg/200, fg/300) | ~5% | Supporting text, dividers, captions |
| Crème 200 | ~5% | Warm card backgrounds, secondary surfaces |
| Orange 100 | ~5% | Accents, CTAs, labels, highlights |
| Red 200 | ~5% | Supporting accent, deeper brand moments |

---

## Headline Colour Treatment

Headlines use a two-line contrast treatment to create visual rhythm without
introducing additional colours:

- **Line 1 (primary statement):** Black `#000000` on light colourway / White `#FFFFFF` on dark colourway
- **Line 2 (secondary / contrast):** `fg/neutral/200` — Black at 60% opacity on light / White at 60% opacity on dark

This treatment is used consistently across social, editorial, and marketing layouts.
Never use a brand colour (orange, red, crème) for headline text.

---

## Text Accessibility

- Text should only appear in **black or white** as a base rule
- On orange or crème backgrounds, use **black** text
- On dark/black backgrounds, use **white** text
- `fg/neutral/200` (60% opacity) is safe for secondary text on white or black
- Never use coloured text on coloured backgrounds

---

## Legacy Colours — Do Not Use

Blue (`#3B5EDB` approx.) was used in 2024–2025 as a supporting accent across
labels, checkpoints, and UI indicators. **Blue should not appear in any new designs.**

---

## Misuse — What to Avoid

- Don't use gradient fills as primary backgrounds
- Don't use yellow or any colour outside the palette as a headline colour
- Don't use orange as a large background fill
- Don't use blue tones in any new work
- Don't apply low-contrast colour pairings (e.g. light grey text on white)
