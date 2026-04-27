# Design System: 59ST CONSTRACTION
**Source URL:** https://fn-constraction.gr/

> *"Crafting spaces with precision, innovation, and style."*

This document distills the visual language of 59ST CONSTRACTION's website into a semantic design system. It is the source of truth for prompting Stitch (or any generative tool) to produce new screens that align faithfully with the existing brand.

---

## 1. Visual Theme & Atmosphere

The aesthetic is **architectural-editorial** — the calm, considered pacing of a high-end interiors magazine rather than a corporate construction site. The mood is **moody, cinematic, and craftsmanship-forward**: full-bleed photography of industrial lofts (exposed brick, concrete ceilings, dark steel, warm lamplight) is paired with a hushed, airy left sidebar that breathes white space.

The character is **restrained, masculine, and premium**. Decoration is minimal; warmth comes from a single bronze accent and from the photography itself. Every surface and edge is **sharp and squared-off** — there is no softness in the geometry, only in the imagery. The reader is invited to slow down: long vertical rhythms, generous whitespace, and headlines that whisper in wide-tracked uppercase rather than shout.

If this site were a physical object, it would be a hand-bound architecture monograph — heavy, matte-paper, gold-foiled at the spine.

---

## 2. Color Palette & Roles

The palette is **near-monochromatic** — a disciplined neutral spectrum lit by a single warm metallic accent. This restraint is intentional: the photography supplies all chromatic interest, and the chrome stays out of its way.

* **Architect's Bronze** (`#B19777`) — The sole brand accent and signature color. Used exclusively for the *ConstrAction* wordmark, the eyebrow micro-tracking text (`ΤΕΧΝΙΚΗ ΕΤΑΙΡΕΙΑ`), and the thin L-shaped corner brackets that frame hero imagery. Functions as a metallic foil: rare, deliberate, ornamental.
* **Charcoal Ink** (`#272727`) — Primary heading color on light surfaces. Used for all section titles (`ΤΑ ΕΡΓΑ ΜΑΣ`, `ΥΠΗΡΕΣΙΕΣ`, `59ST CONSTRACTION`). Just shy of true black for a softer, printed-ink feel.
* **Quiet Slate** (`#777777`) — Body copy and secondary text. Establishes a calm, low-contrast reading register that recedes behind headlines and imagery.
* **Whisper Gray** (`#FAFAFA`) — Alternating section surface for subtle horizontal banding between content blocks. So light it reads as a tonal shift rather than a true color change.
* **Pure Canvas** (`#FFFFFF`) — Primary background and the entire left sidebar. The dominant negative space of the site.
* **Cinematic Black** (`#000000`) — Reserved for photographic overlays, deep shadow detail in hero imagery, and the dramatic dark interiors that anchor the hero slider.

---

## 3. Typography Rules

The system runs on **two typefaces only**, in clear and confident roles:

* **Oswald** *(condensed sans-serif, weights 300–400)* — All headings, navigation labels, eyebrow text, and section titles. Always set in **uppercase** with **dramatic letter-spacing** that grows with hierarchy. Its narrow proportions evoke architectural drafting and editorial mastheads.
* **Didact Gothic** *(humanist sans-serif, weight 400)* — All body copy, paragraphs, and form/button labels. Open, legible, and warm — the calm counterpoint to Oswald's verticality.

**Hierarchy and tracking character**:

| Tier | Font | Size · Line-height | Letter-spacing | Color |
|---|---|---|---|---|
| Section Title (`ΤΑ ΕΡΓΑ ΜΑΣ`) | Oswald 400 UPPERCASE | 40 / 50 px | **10 px** (extreme) | Charcoal Ink |
| Hero Title (over photography) | Oswald 400 UPPERCASE | 30 / 40 px | **15 px** (theatrical) | Pure Canvas |
| Sub-heading (h4) | Oswald 300 UPPERCASE | 20 / 25 px | **5 px** (refined) | Charcoal Ink |
| Eyebrow / Brand Tagline | Oswald 400 UPPERCASE | 10 / 10 px | **9 px** (precision) | Architect's Bronze |
| Body | Didact Gothic 400 | 16–18 / 28–31 px | normal | Quiet Slate |

**Rule of thumb:** *Headings are never lowercase, never tight-tracked, and never coloured outside the Charcoal–Bronze–Canvas trio. Body text never uses Oswald.* Letter-spacing scales with importance — the bigger the statement, the wider the breath between letters.

---

## 4. Component Stylings

* **Buttons** — Sharp-cornered outline rectangles with a **1 px hairline stroke** in the foreground color, **transparent fill**, and an uppercase label set in the body sans. No drop shadow, no rounding, no fill on hover by default. The hero language toggle (`ENG`) is the canonical example: a thin white frame on dark photography. Buttons feel like printed map keys, not interactive chrome.
* **Cards / Project Tiles** — **Squared, edge-to-edge photographic tiles** with no rounding and no drop shadow. The project name (e.g. `BUNA TETU`, `ΚΤΗΡΙΟ ΟΤΕ`) is set in Oswald uppercase and overlaid directly on the photograph in Pure Canvas, often above a small Architect's Bronze eyebrow line. Imagery may be ornamented with thin **bronze L-shaped corner brackets** that frame the photo like a museum mount.
* **Inputs / Forms** — Hairline strokes, sharp corners, generous internal padding. Minimal label decoration; placeholder text in Quiet Slate. Visual language matches buttons exactly so the contact form reads as a continuous typographic surface, not a UI control panel.
* **Navigation** — A **vertical, text-only menu** stacked in the left sidebar (`ΑΡΧΙΚΗ`, `ΕΤΑΙΡΕΙΑ`, `ΤΑ ΕΡΓΑ ΜΑΣ`, `ΥΠΗΡΕΣΙΕΣ`, `BLOG`, `ΕΠΙΚΟΙΝΩΝΙΑ`). Uppercase Didact Gothic, wide-tracked, **no underlines, no bullets, no icons**. The active state is implied by hierarchy alone. The bronze accent is reserved strictly for the logo and brand eyebrow — never for menu hover.
* **Iconography & Ornament** — Almost absent. The only repeating ornaments are the **thin bronze L-bracket corner frames** around hero imagery and a single Instagram glyph in the sidebar foot. No service icons, no decorative dividers, no illustration.

---

## 5. Layout Principles

The page is built on a **two-zone editorial split**:

* **Left Rail (≈30 % of viewport, fixed)** — Pure Canvas background. Holds the bronze logo wordmark, the vertical text menu, and a single Instagram glyph at the foot. This rail is the site's "spine" — quiet, persistent, almost stationery-like.
* **Right Stage (≈70 %)** — Reserved for full-bleed imagery, hero sliders, and editorial content blocks. Each section pairs *one dominant photograph* with *one concise typographic block*. There is no multi-column grid; the rhythm is **vertical and cinematic**, not gridded.

**Containers and spacing**: Content is constrained to **1140 px max-width**. The spacing scale is generous and progressive: `0.44 · 0.67 · 1 · 1.5 · 2.25 · 3.38 · 5.06 rem` — vertical breathing room grows roughly geometrically, which gives the page its slow editorial pace.

**Elevation and depth**: **Flat.** No drop shadows on cards, headings, or buttons. Depth is created entirely by the contrast between airy white sidebar and dark, full-bleed photography — by *content*, not by *effects*.

**Composition rule of thumb**: *One photograph, one heading, one paragraph, per section.* If a layout requires more than that, split it into two stacked sections rather than fragmenting the surface.

---

## 6. Voice & Content Atmosphere

While not a visual token, the copy reinforces the design: short, declarative, craftsmanship-forward Greek/English bilingual prose ("we specialize in transforming your visions into reality"). Headlines are nouns and infinitives, never sales-speak. New screens should preserve this calm, technical-yet-poetic register — the typography assumes it.
