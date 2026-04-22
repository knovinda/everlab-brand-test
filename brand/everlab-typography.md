# Everlab — Typography

We have three typefaces in our brand toolkit: a headline typeface, a secondary
sans, and a mono. These are used for different needs across marketing and
editorial contexts. For product design, refer to the product design system.

---

## Typefaces

### Tobias — Display / Headline
Used for large display moments, hero headlines, and editorial-led layouts.
High-impact, distinctive, sets the brand tone.

### Saans — Primary Sans
The workhorse typeface. Used for body copy, UI labels, supporting text,
and anywhere legibility is the priority.

### Saans Mono — Monospace
Used for data, biomarker labels, technical callouts, and any context where
a clinical or precision feel is needed.

---

## Google Fonts Fallbacks

For contexts where brand fonts aren't available (e.g. email, external docs):

- **Tobias** → STIX Two Text
- **Saans** → Inter
- **Saans Mono** → Inter (mono variant)

Backup system fonts: Times New Roman (serif), Arial (sans-serif)

---

## Type Scale

Format: `size/line-height` in px. Weight shown as numeric value.

### Display (Tobias)

| Token | Weight | Size / Line-height | Usage |
|---|---|---|---|
| Display 400 | 400 | 32 / 32 | Large editorial headlines |
| Display 300 | 300 | 36 / 38 | Hero statements |
| Display 200 | 200 | 26 / 28 | Mid-size display |
| Display 100 | 100 | 20 / 22 | Small display |

### Headlines (Saans)

Primary headlines use Saans. Two variants: default and secondary.

| Token | Weight | Size / Line-height |
|---|---|---|
| Headline 800 | 800 | 32 / 32 |
| Headline 700 | 700 | 24 / 24 |
| Headline 600 | 600 | 18 / 22 |
| Headline 500 | 500 | 16 / 20 |
| Headline 400 | 400 | 14 / 18 |
| Headline 300 | 300 | 12 / 16 |
| Headline 200 | 200 | 10 / 14 |
| Headline 100 | 100 | 12 / 14 |

> Secondary headlines follow the same scale and sizing — used for
> supporting hierarchy where primary headlines are already established.

### Body (Saans)

Each body size comes in four variants: Medium, Regular, Medium cap, Regular cap.

| Token | Size / Line-height |
|---|---|
| Body 600 | 24 / 26 |
| Body 500 | 20 / 22 |
| Body 400 | 18 / 22 |
| Body 300 | 16 / 20 |
| Body 200 | 14 / 18 |
| Body 100 | 12 / 14 |

### Label — Body (Saans)

| Token | Size / Line-height |
|---|---|
| Label Body 400 | 20 / 24 |
| Label Body 300 | 16 / 18 |
| Label Body 200 | 14 / 16 |
| Label Body 100 | 12 / 14 |

Each label size comes in: Medium, Regular, Medium cap, Regular cap.

### Label — Mono (Saans Mono)

Used for biomarker names, data labels, clinical callouts, and precision contexts.

| Token | Size / Line-height |
|---|---|
| Label Mono 600 | 24 / 26 |
| Label Mono 500 | 20 / 22 |
| Label Mono 400 | 18 / 22 |
| Label Mono 300 | 16 / 20 |
| Label Mono 200 | 14 / 18 |
| Label Mono 100 | 12 / 14 |

Each comes in: Medium, Regular, Medium cap, Regular cap.
Label Mono 100 also includes a Semibold variant.

---

## Headline Colour Treatment

Headlines use a two-line contrast system for visual rhythm:

- **Line 1 (primary):** `fg/neutral/primary/100` — Black on light / White on dark
- **Line 2 (secondary):** `fg/neutral/primary/200` — Black at ~60% opacity on light / White at ~60% opacity on dark

Never use orange, red, or crème for headline text.

---

## Type Pairing — Marketing Contexts

| Context | Typeface | Style |
|---|---|---|
| Hero headline line 1 | Tobias | Display 300–400, full opacity |
| Hero headline line 2 | Tobias | Display 300–400, 60% opacity |
| Section headline | Saans | Headline 700–800 |
| Body / editorial copy | Saans | Body 300–400, Regular |
| Biomarker / data labels | Saans Mono | Label Mono 200–300 |
| CTA / button labels | Saans | Label Body 200–300, Medium cap |
| Captions / supporting | Saans | Body 100–200, Regular |

---

## Misuse — What to Avoid

- Don't mix Tobias and Saans at the same hierarchy level
- Don't use Tobias for body copy or small text
- Don't use light weights (100–200) at small sizes
- Don't use all-caps on display or headline sizes
- Don't stretch, condense, or alter the typefaces
- Don't use system fonts in designed marketing outputs
