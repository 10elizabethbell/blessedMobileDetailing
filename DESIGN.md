---
name: Blessed Mobile Detailing
description: Mobile auto detailing for Ocean County, NJ, recorded as the snow-foam pass.
colors:
  gold: "#c8962e"
  gold-bright: "#e2b54a"
  gold-ink: "#85600f"
  rinse: "#155a88"
  rinse-deep: "#0f4a72"
  water: "#1d6fa5"
  rinse-text-soft: "#d5e6f2"
  ripple-light: "#9cc3de"
  foam: "#fbfcfd"
  mist: "#eef4f8"
  line: "#d3e0e9"
  ink: "#14171a"
  ink-soft: "#3d4a55"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2.75rem, 12.5vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 7vw, 3.5rem)"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "-0.03em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.35rem, 4.4vw, 1.75rem)"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "-0.015em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.125rem, 2.4vw, 1.375rem)"
    fontWeight: 400
    lineHeight: 1.45
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "0.01em"
rounded:
  pill: "999px"
  round: "50%"
  focus: "6px"
spacing:
  gutter: "clamp(1rem, 5vw, 3rem)"
  max: "72rem"
  section: "clamp(3.5rem, 9vw, 6.5rem)"
  row: "1.5rem"
  stack: "0.75rem"
components:
  button-primary:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0.9rem 1.5rem"
    height: "3.5rem"
  button-primary-hover:
    backgroundColor: "{colors.gold-bright}"
    textColor: "{colors.ink}"
  button-primary-active:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.gold-bright}"
  button-secondary:
    backgroundColor: "#ffffff"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0.9rem 1.5rem"
    height: "3.5rem"
  button-secondary-hover:
    backgroundColor: "{colors.mist}"
    textColor: "{colors.ink}"
  button-secondary-active:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.gold-bright}"
  link-quote:
    textColor: "{colors.water}"
  link-quote-hover:
    textColor: "{colors.rinse-deep}"
  sticky-call:
    backgroundColor: "#ffffff"
    textColor: "{colors.ink}"
    rounded: "{rounded.round}"
    size: "3.5rem"
---

# Design System: Blessed Mobile Detailing

## Overview

**Creative North Star: "The Snow-Foam Pass"**

The page is the moment a car starts getting clean: a bright mass of suds settling along the bottom of a cool mist-blue hero, beads of water on a rinse-blue band, and gold trim held back for the things that matter. The ground is cool foam white and mist, never dark; depth comes from foam, water, and the round gold-ringed logo medallion, not from photography or card stacks.

Density is low and the voice is loud. Every heading is heavy uppercase system sans, tightly tracked, set large enough to read from arm's length on a phone. Content runs as ruled lists and big numerals rather than boxed cards, and sections hand off through tinted bands joined by ripple seams: foam to mist to rinse and back to foam. The one interaction that matters (text to book) is always a gold pill, and on phones it is one thumb away in a sticky bar that steps aside while the hero's own buttons are visible.

Gold is the brand's thread from the black-and-gold logo, but it is rationed: in this light world it reads as trim, never as a field. The world rejects the category default of a dark hero over a car photo followed by an icon-card grid.

**Key Characteristics:**
- Cool light ground: foam white and mist blue, with one saturated rinse-blue band.
- Heavy uppercase system sans (800-900) for every heading; regular weight body in ink-soft.
- Gold rationed to the primary action, solid dot marks, focus/selection, the logo ring, and the H1 word BLESSED.
- Ruled lists and giant numerals instead of cards.
- Procedural world materials: foam cell mass, water beading, ripple seams.
- Pills and circles only; no rectangles with corners.

## Colors

A cool water palette (foam, mist, rinse) with a single metallic gold accent rationed to marks and the primary action.

### Primary
- **Metallic Gold** (gold): the primary action's fill, solid service dots, the focus outline, the text caret, and the 2-3px ring around every logo instance. Always carries ink text when it is a fill.
- **Polished Gold** (gold-bright): hover state of the primary action, the pressed-state text color, town dots on the rinse band, and the text selection background.
- **Deep Gold Ink** (gold-ink): gold as text on light grounds. Used for the H1 word BLESSED, the deliberate echo of the logo lockup; the brighter golds fail as text on foam and mist.

### Secondary
- **Rinse Blue** (rinse): the one saturated field (the service-area band), the step numerals, and the accent line of the closing headline.
- **Deep Rinse** (rinse-deep): hover state for blue text links.
- **Water Blue** (water): links, the "Text for a quote" action, icon tint for location, the dark ripple seam stroke, and the scrollbar thumb.
- **Rinse Haze** (rinse-text-soft): secondary text on the rinse band.
- **Spray Blue** (ripple-light): ripple seam stroke where a seam touches the rinse band.

### Neutral
- **Foam White** (foam): page ground, services and close sections, the foam mass fill, sticky bar ground (at 94% with blur).
- **Mist** (mist): the how-it-works band and footer; the hero runs a mist gradient (#edf3f8 to #e6eff6 with a #d9e8f2 radial at top right) so the white foam mass reads against it.
- **Waterline** (line): hairline row dividers, footer and sticky-bar top borders, the medallion's outer ring.
- **Ink** (ink): headings, primary button text, the heavy 2px rule that opens the services list, the pressed-button fill.
- **Soft Ink** (ink-soft): body copy, pitch, descriptions, footer text.

### Named Rules
**The Gold Trim Rule.** Gold is trim, not a field. It appears only as the primary action fill, small solid dot marks, focus/selection/caret, the logo ring, and the single gold word in the H1. Step numerals, headline accents, links, and secondary buttons are blue or ink, never gold.

**The Gold-As-Text Rule.** When gold has to be read as text on a light ground, it is gold-ink. The mid and bright golds are fills and marks only.

**The One Rinse Band Rule.** Rinse blue is a full-bleed field exactly once per page; every other band is foam or mist.

## Typography

**Display Font:** System sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial) — user-pinned
**Body Font:** Same stack
**Label/Mono Font:** Same stack; numerals use tabular figures for phone numbers

**Character:** One family driven entirely by weight and case. Headings are 900-weight uppercase with negative tracking, so the system sans reads as signage painted on a van door; body stays regular and soft-inked so the shouting stays in the headings. The family is a user pin (PRODUCT.md), not a stylistic preference to extend.

### Hierarchy
- **Display** (900, clamp(2.75rem, 12.5vw, 6rem), 0.92, -0.035em, uppercase): the hero H1 only, broken onto two lines with the first word in gold-ink.
- **Display numerals** (900, clamp(4.5rem, 18vw, 7.5rem), 0.8, -0.05em, rinse): process step numbers, used as the visual anchor in place of icons.
- **Headline** (900, clamp(2rem, 7vw, 3.5rem), 1.05, -0.03em, uppercase): section headings. The closing headline and town names scale up to the display range (up to 4.5rem and 4rem) in the same treatment.
- **Title** (800, clamp(1.35rem, 4.4vw, 1.75rem), 1.15, -0.015em, sentence case): service names and step titles. The lead service steps up to clamp(1.75rem, 6vw, 2.5rem).
- **Lead** (400, clamp(1.125rem, 2.4vw, 1.375rem), 1.45, ink-soft, max 30ch): the hero pitch; section intros run 1.125rem at 40-46ch.
- **Body** (400, 1.0625rem, 1.6, ink-soft): descriptions, capped at 34-52ch.
- **Label** (700-800, 1.0625rem, 0.01em): button text and the phone link. The wordmark next to the logo is 800 uppercase at 0.9-0.95rem with 0.02em tracking.

### Named Rules
**The Weight Carries It Rule.** Hierarchy is built with weight (900 / 800 / 400), case, and size, never with a second family or color changes for emphasis. Every H1/H2 is uppercase 900 with negative tracking; every H3 is sentence-case 800.

**The Balanced Heading Rule.** Headings use text-wrap: balance and body uses text-wrap: pretty, at 1.05 line-height for headings.

## Layout

Single column on phones, centered container of 72rem with fluid gutters (clamp(1rem, 5vw, 3rem)). Sections are full-bleed tinted bands with vertical padding of clamp(3.5rem, 9vw, 6.5rem); the band sequence is mist hero, foam services, mist how-it-works, rinse service area, foam close, mist footer.

Breakpoints: at 760px the header phone link appears, the sticky bar disappears, and the footer goes two-column. At 900px the hero splits 1.25fr / 0.75fr with the logo medallion on the right; hero buttons go inline and the primary grows (3.875rem tall, 1.1875rem text); services go 0.8fr / 1.2fr with a sticky heading column and the quote link right-aligned in each row; steps become three columns; town names flow inline instead of stacking.

Lists are ruled, not boxed: rows of 1.5rem vertical padding (2rem for the lead row) separated by 1px waterline hairlines, opened by a 2px ink rule. On phones hero buttons stack full width (max 26rem) with a 0.75rem gap, and the body reserves 5.5rem plus safe-area inset at the bottom for the sticky bar.

## Elevation & Depth

Mostly flat with tonal banding. Depth comes from the world's materials (foam, beading, the medallion) and from soft, tinted shadows that sit under the gold and around the logo; no surface is lifted as a card.

### Shadow Vocabulary
- **Gold lift** (`box-shadow: 0 1px 0 rgba(255,255,255,.55) inset, 0 6px 18px -6px rgba(133,96,15,.55)`): primary button at rest; deepens to `0 10px 24px -8px` on hover with a 1px rise.
- **Medallion halo** (`box-shadow: 0 0 0 3px gold, 0 0 0 10px #fff, 0 0 0 11px line, 0 30px 60px -20px rgba(15,74,114,.45)`): the large hero logo; the header/footer logo uses a 2px gold ring plus a small ink drop.
- **Sticky veil** (`box-shadow: 0 -8px 24px -12px rgba(15,74,114,.25)` with `backdrop-filter: saturate(1.4) blur(12px)`): the mobile booking bar.
- **Bead** (inset dark bottom, inset light top, 2-3px outer drop in deep rinse): water drops on the rinse band.

### Named Rules
**The Tinted Shadow Rule.** Shadows are tinted by what casts them: gold-brown under gold, rinse-navy under the medallion and sticky bar. No neutral grey drop shadows and no hard offset shadows.

**The Press Flattens Rule.** Pressing any button removes its shadow and lift and inverts it to ink with gold-bright text.

## Shapes

Only two silhouettes: the pill (999px) for buttons and the circle for the logo, dot marks, town dots, the sticky call button, and water beads (slightly flattened, 50% 50% 48% 48% / 46% 46% 54% 54%). Everything else is unbounded: sections are full-bleed bands, lists are ruled rows, and there are no cornered cards. Borders are hairlines (1px waterline) or deliberate rules (2px ink top rule on the service list, 1.5px underline on quote links). Section joins are ripple seams: three stacked quadratic wave strokes, 1.5px non-scaling, 28px tall, drawn over a hard 50/50 split of the two adjoining band colors.

## Components

### Buttons
Big, round, and physical: they rise on hover and invert on press.
- **Shape:** full pill (999px), minimum 3.5rem tall, 0.9rem x 1.5rem padding, 0.6rem gap between leading stroke icon and label.
- **Primary (gold):** gold fill, ink text, 800 weight, gold lift shadow. Hover goes gold-bright and rises 1px. Used for "Tap to Text & Book" only.
- **Secondary (line):** white fill, ink text at 700, 1.5px cool-grey border (#b7c8d4). Hover fills mist and darkens the border to ink-soft. Used for Call; deliberately quieter than the primary.
- **Press (all):** ink fill, gold-bright text, ink border, no shadow, no transform.
- **Focus:** 3px gold outline, 3px offset, 6px radius.
- **Motion:** 0.18s color transitions and 0.25s shadow/transform transitions on cubic-bezier(.16, 1, .3, 1).

### Service Menu (signature)
A ruled list, not a card grid. Each row: a solid gold dot (1.05rem; 1.35rem on the lead row), a title-weight service name, a soft-ink description, and a water-blue "Text for a quote" link with a 1.5px underline and an arrow that slides 3px on hover. The lead row (the flagship service) gets more padding and a larger title.

### Step Numerals
Giant 900-weight rinse-blue numerals beside (phone) or above (desktop) a title and one sentence. They replace icons as the step marker.

### Town List
Town names in headline-scale uppercase white on the rinse band, each preceded by a gold-bright dot sized at 0.26em; a sentence-case rinse-haze line closes the list.

### Navigation
No menu. The header is the logo (44px circle with gold ring) plus uppercase wordmark, with the phone number (tabular figures, ink, water-blue on hover) appearing at 760px and up.

### Sticky Booking Bar (mobile)
Fixed bottom bar below 760px: foam at 94% with blur, a hairline top border, a full-width gold primary, and a 3.5rem circular call button (white, 2px ink border, inverts on press). It slides out (0.45s) while the hero buttons are in view and returns once they scroll away.

### Foam Bank (signature)
A procedural SVG along the bottom of the hero: one foam-white mass with a turbulence-displaced crest and a soft upward shadow, packed with jittered suds cells (1.6-4.2 unit radius, occasional larger bubbles near the crest, #c2d3e0 strokes fading with depth). Cells scale 1.8x below 600px. With motion allowed, the bank settles in over 2.2s and a few crest cells pop.

### Water Beading (signature)
About 70 flattened, rinse-tinted domes clustered in the rinse band's top-right, masked to fade out; on phones they collapse to a thin strip along the top edge.

## Do's and Don'ts

### Do:
- **Do** keep every ground cool and light (foam, mist), with rinse blue as the single saturated band.
- **Do** reserve gold for the primary action, dot marks, focus/selection, the logo ring, and the gold-ink H1 word.
- **Do** set every H1/H2 in 900-weight uppercase with -0.03 to -0.035em tracking.
- **Do** present offerings as ruled rows with dot marks and lists of big type, not boxed cards.
- **Do** join bands with ripple seams drawn over a 50/50 split of the adjoining colors, at 0.35 stroke opacity in water blue or 0.75 in spray blue next to rinse.
- **Do** make the primary action a gold pill with ink text, and invert every button to ink with gold-bright text on press.
- **Do** keep the booking action one thumb away on phones via the sticky bar, hidden while the hero CTAs are visible.
- **Do** honor reduced motion: foam settle, cell pops, and smooth scroll all switch off.

### Don't:
- **Don't** use a dark hero over a car photo or a grid of icon cards.
- **Don't** use gold for large fields, step numbers, headline accents, links, or secondary buttons.
- **Don't** set gold-bright or gold as text on foam or mist; use gold-ink.
- **Don't** add ornament outside the world's materials (foam, water beading, ripple seams, the logo medallion).
- **Don't** introduce cornered cards, square buttons, or hard offset shadows.
