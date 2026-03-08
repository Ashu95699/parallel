## design-guidelines.md (Brutalist Hybrid Version)

### Emotional Tone

**Feels like a bold independent film archive — raw, editorial, and unapologetically cinematic.**

Imagine:

* an **indie film festival catalog**
* a **Swiss poster grid**
* a **brutalist art gallery website**

The interface should feel:

* confident
* graphic
* cinematic
* deliberate

Not soft. Not decorative.

The design should feel like **a film poster wall**, where typography and layout dominate.

This follows the Lovable philosophy: design the **feeling first**, then the interface. 

---

# Visual System

## Typography

Typography becomes the **primary visual element**.

Brutalist interfaces rely on:

* oversized headlines
* strong hierarchy
* confident spacing

---

### Typeface Roles

**Primary Typeface — Bold Grotesk Sans**

Used for:

* film titles
* headlines
* section labels

Style:

* geometric
* neutral
* bold

Good examples:

* **Space Grotesk**
* **Suisse Intl**
* **Inter Tight**

---

**Secondary Typeface — Monospace**

Used for:

* metadata
* ratings
* technical info

Examples:

* **IBM Plex Mono**
* **JetBrains Mono**

This reinforces the **archive / data catalog feeling**.

---

### Typographic Hierarchy

| Level | Usage              | Size    | Weight |
| ----- | ------------------ | ------- | ------ |
| H1    | Film titles / hero | 56–72px | 700    |
| H2    | Section titles     | 36–40px | 600    |
| H3    | Movie card titles  | 20–24px | 600    |
| Body  | Paragraph text     | 16–18px | 400    |
| Meta  | Film metadata      | 13–14px | Mono   |

Rules:

* tight vertical rhythm
* bold headings
* clear separation between editorial text and metadata

---

# Color System

Brutalist design thrives on **extreme simplicity**.

### Primary

Deep black.

Hex
`#000000`

RGB
`0,0,0`

Emotion:

* confident
* graphic
* archival

---

### Background

Pure white.

Hex
`#FFFFFF`

RGB
`255,255,255`

Creates **maximum contrast**.

---

### Accent

Cinematic red.

Hex
`#E10600`

RGB
`225,6,0`

Used for:

* ratings
* active states
* watchlist markers

---

### Secondary

Neutral grey.

Hex
`#9CA3AF`

Used for metadata.

---

### Semantic Colors

Success
`#16A34A`

Error
`#DC2626`

Maintain **WCAG AA contrast**.

---

# Spacing & Layout

Use a **strict grid system**.

### Grid System

12-column grid.

Breakpoints:

Desktop
12 columns

Tablet
8 columns

Mobile
4 columns

---

### Spacing Scale

8pt grid:

| Token | Size |
| ----- | ---- |
| xs    | 8px  |
| sm    | 16px |
| md    | 24px |
| lg    | 32px |
| xl    | 48px |
| xxl   | 72px |

Brutalist design uses **clear structure**, not decorative spacing.

---

# Layout Patterns

## Movie Directory

Poster grid with strong structure.

Example:

Desktop

```
4 posters per row
```

Each card contains:

Poster
Title
Year
Director

Hover reveals actions:

Add to Watchlist

---

## Watchlist Layout

Two bold sections:

```
TO WATCH
WATCHED
```

Displayed in stacked blocks.

Large labels reinforce the brutalist feel.

---

## Movie Detail Page

Brutalist editorial layout:

Left column:

Poster

Right column:

Title
Director
Year
Country
Runtime

Below:

Ratings
Review

---

# Motion & Interaction

Brutalist design prefers **minimal motion**.

Motion should feel:

* direct
* functional
* quick

Lovable design advice emphasizes describing **interaction behavior** rather than static UI. 

---

### Motion Timing

150–200ms

Fast and decisive.

---

### Hover Behavior

Poster cards:

* sharp shadow
* slight scale (1.02)

No soft easing.

---

### Drag Interaction

Dragging movie cards should feel **mechanical and precise**.

Interaction flow:

drag → watchlist highlight border → drop

Confirmation appears instantly.

---

### Rating Interaction

Star rating:

* immediate fill
* no bounce animation

Brutalist systems avoid playful motion.

---

# Voice & Tone

Tone should feel **cinephile and editorial**.

Avoid:

* gamification
* emojis
* marketing language

---

### Microcopy Examples

Add to Watchlist

Mark as Watched

Write your 50-word review.

---

### Empty State

“No films logged yet.
Start with the last movie you watched.”

---

# System Consistency

Anchor patterns to clear systems.

Design references:

* **Swiss modernist posters**
* **Brutalist web layouts**
* **editorial magazine grids**

Consistency rules:

* identical poster card structure
* rating placement always below metadata
* watchlist actions always top-right

---

# Accessibility

Even brutalist interfaces must remain accessible.

### Structure

Clear heading hierarchy.

H1 → H2 → H3

---

### Keyboard Navigation

Users must navigate:

* movie cards
* rating stars
* watchlist buttons

without a mouse.

---

### Focus States

Use strong outline:

```
outline: 3px solid red
```

Clear and visible.

---

### Screen Readers

ARIA labels required for:

* star ratings
* drag actions
* watchlist buttons

---

# Emotional Audit Checklist

Ask during design:

* Does the layout feel **bold and confident**?
* Is typography doing the **visual heavy lifting**?
* Does the grid feel **structured and intentional**?
* Are films the **visual center of attention**?

If the interface feels soft or decorative, simplify.

---

# Technical QA Checklist

Before release verify:

* typography aligns to grid
* color contrast passes WCAG AA
* interactive states are obvious
* motion remains under 200ms

---

# Design Snapshot

### Emotional Thesis

```
A brutalist cinema archive — bold typography, strict grids, and unapologetic focus on film.
```

---

### Color Palette

```
Black: #000000
White: #FFFFFF
Accent Red: #E10600
Grey: #9CA3AF
Success: #16A34A
Error: #DC2626
```

---

### Typography Scale

| Element | Size      |
| ------- | --------- |
| H1      | 72px      |
| H2      | 40px      |
| H3      | 24px      |
| Body    | 16–18px   |
| Meta    | 13px mono |

---

### Layout System

* 12-column grid
* poster wall browsing
* bold editorial headings
* minimal decoration

---

# Design Integrity Review

This brutalist hybrid direction aligns strongly with CineTrack’s concept.
The strict grid, oversized typography, and stark palette give the product the feel of an **independent cinema archive rather than a social app**.

One improvement:

Introduce **large cinematic hero typography on movie pages**, allowing film titles to occupy dramatic screen space similar to **festival posters**.

---

✅ **Design regenerated with Brutalist Hybrid direction**

Next (optional but very useful):

I can also generate a **Lovable-ready master prompt** that will produce **a much better UI inside Lovable** for CineTrack.

Just say:

**“Generate the Lovable v2 prompt.”** 🎬
