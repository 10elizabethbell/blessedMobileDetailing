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
    fontSize: "clamp(2.6rem, 11.5vw, 5.25rem)"
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
  row-go:
    textColor: "{colors.water}"
    border: "1.5px solid {colors.line}"
  row-go-hover:
    backgroundColor: "{colors.water}"
    textColor: "#ffffff"
  sticky-call:
    backgroundColor: "#ffffff"
    textColor: "{colors.ink}"
    rounded: "{rounded.round}"
    size: "3.5rem"
---

# Design System: Blessed Mobile Detailing

## Overview

**Creative North Star: "The Snow-Foam Pass"**

The page is the moment a car starts getting clean: a bright, living bank of suds along the bottom of a cool mist-blue hero, the client's own finished work held up in soap bubbles riding that foam, beads of water on a rinse-blue band, and gold trim held back for the things that matter. The ground is cool foam white and mist, never dark; depth comes from foam, glass, and water. Photography appears only as real work framed by the world's own material (a soap bubble), never as a full-bleed background or a cornered card.

Density is low and the voice is loud. Every heading is heavy uppercase system sans, tightly tracked, set large enough to read from arm's length on a phone. Content runs as ruled lists and big numerals rather than boxed cards, and sections hand off through tinted bands joined by ripple seams: foam to mist to rinse and back to foam. The one interaction that matters (text to book) is always a gold pill, and on phones it is one thumb away in a sticky bar that steps aside while the hero's own buttons are visible.

Gold is the brand's thread from the black-and-gold logo, but it is rationed: in this light world it reads as trim, never as a field. The world rejects the category default of a dark hero over a car photo followed by an icon-card grid.

**Key Characteristics:**
- Cool light ground: foam white and mist blue, with one saturated rinse-blue band.
- Heavy uppercase system sans (800-900) for every heading; regular weight body in ink-soft.
- Gold rationed to the primary action, solid dot marks, focus/selection, the logo ring, and the word BLESSED in the closing heading.
- Ruled lists and giant numerals instead of cards.
- World materials, all bubble-and-water: a live canvas foam bank, glass photo bubbles, loose rising bubbles, water beading, ripple seams.
- Round forms only: pills and circles; no rectangles with corners.

## Colors

A cool water palette (foam, mist, rinse) with a single metallic gold accent rationed to marks and the primary action.

### Primary
- **Metallic Gold** (gold): the primary action's fill, solid service dots, the focus outline, the text caret, and the 2px ring around every logo instance. Always carries ink text when it is a fill.
- **Polished Gold** (gold-bright): hover state of the primary action, the pressed-state text color, town dots on the rinse band, and the text selection background.
- **Deep Gold Ink** (gold-ink): gold as text on light grounds. Used for the word BLESSED in the closing heading, the deliberate echo of the logo lockup; the brighter golds fail as text on foam and mist.

### Secondary
- **Rinse Blue** (rinse): the one saturated field (the service-area band), the step numerals, and the second line of the hero headline (YOUR DRIVEWAY.).
- **Deep Rinse** (rinse-deep): hover state for blue text links; the tint of every navy shadow (sticky bar, photo bubbles).
- **Water Blue** (water): links, the service rows' circular arrow cue, icon tint for location, the dark ripple seam stroke, and the scrollbar thumb.
- **Rinse Haze** (rinse-text-soft): secondary text on the rinse band.
- **Spray Blue** (ripple-light): ripple seam stroke where a seam touches the rinse band.

### Neutral
- **Foam White** (foam): page ground, services and close sections, the foam bank's cream fade, sticky bar ground (at 94% with blur).
- **Mist** (mist): the how-it-works band, footer, and the photo bubbles' backing while images load; the hero runs a mist gradient (#edf3f8 to #e6eff6 with a #d9e8f2 radial at top right) so the white foam reads against it.
- **Waterline** (line): hairline row dividers, footer and sticky-bar top borders.
- **Ink** (ink): headings, primary button text, the heavy 2px rule that opens the services list, the pressed-button fill.
- **Soft Ink** (ink-soft): body copy, pitch, descriptions, footer text.

### Named Rules
**The Gold Trim Rule.** Gold is trim, not a field. It appears only as the primary action fill, small solid dot marks, focus/selection/caret, the logo ring, and the single gold-ink word BLESSED where the business name is set as a heading. Step numerals, headline accents, links, and secondary buttons are blue or ink, never gold.

**The Gold-As-Text Rule.** When gold has to be read as text on a light ground, it is gold-ink. The mid and bright golds are fills and marks only.

**The One Rinse Band Rule.** Rinse blue is a full-bleed field exactly once per page; every other band is foam or mist.

## Typography

**Display Font:** System sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial), pinned by the user in PRODUCT.md
**Body Font:** Same stack
**Label/Mono Font:** Same stack; numerals use tabular figures for phone numbers

**Character:** One family driven entirely by weight and case. Headings are 900-weight uppercase with negative tracking, so the system sans reads as signage painted on a van door; body stays regular and soft-inked so the shouting stays in the headings. The family is a user pin, not a stylistic preference to extend to other projects.

### Hierarchy
- **Display** (900, clamp(2.6rem, 11.5vw, 5.25rem), 0.92, -0.035em, uppercase): the hero H1 only, two short declarative lines, the first in ink and the second in rinse blue.
- **Display numerals** (900, clamp(4.5rem, 18vw, 7.5rem), 0.8, -0.05em, rinse): process step numbers, used as the visual anchor in place of icons.
- **Headline** (900, clamp(2rem, 7vw, 3.5rem), 1.05, -0.03em, uppercase): section headings. The closing headline (up to 4.5rem, 0.95 line-height) and town names (up to 4rem) scale toward display size in the same treatment.
- **Title** (800, clamp(1.35rem, 4.4vw, 1.75rem), 1.15, -0.015em, sentence case): service names and step titles. The lead service steps up to clamp(1.75rem, 6vw, 2.5rem).
- **Lead** (400, clamp(1.125rem, 2.4vw, 1.375rem), 1.45, ink-soft, max 30ch): the hero pitch, whose opening clause is set 700 in ink; section intros run 1.125rem at 40-46ch.
- **Body** (400, 1.0625rem, 1.6, ink-soft): descriptions, capped at 34-52ch.
- **Label** (700-800, 1.0625rem, 0.01em): button text and the phone link. The wordmark next to the logo is 800 uppercase at 0.9-0.95rem with 0.02em tracking.

### Named Rules
**The Weight Carries It Rule.** Hierarchy is built with weight (900 / 800 / 400), case, and size, never with a second family. Every H1/H2 is uppercase 900 with negative tracking; every H3 is sentence-case 800. Color shifts inside a heading are whole lines or whole words (a rinse line in the hero, a gold-ink BLESSED in the close), never highlighter fragments.

**The Balanced Heading Rule.** Headings use text-wrap: balance and body uses text-wrap: pretty, at 1.05 line-height for headings.

## Layout

Single column on phones, centered container of 72rem with fluid gutters (clamp(1rem, 5vw, 3rem)). Sections are full-bleed tinted bands with vertical padding of clamp(3.5rem, 9vw, 6.5rem); the band sequence is mist hero, foam services, mist how-it-works, rinse service area, foam close, mist footer.

The hero is a stage for the foam: 12.5rem of bottom padding reserves the bank (clamp(12rem, 22vw, 14rem) tall), and the photo-bubble pair sits behind it with a negative bottom margin so the suds lap its base. Below 600px the pair (23rem max, square) is centered under the copy; from 600px it is 26rem and right-aligned, still stacked under the copy. Only at 1150px and up does the hero split into two columns (1.45fr / 0.55fr): the pair grows to clamp(24rem, 34vw, 32rem), aligns to the bottom of the row, and bleeds past its column by one gutter toward the page edge.

Other breakpoints: at 760px the header phone link appears, the sticky bar disappears, and the footer goes two-column. At 900px hero buttons go inline and the primary grows (3.875rem tall, 1.1875rem text); services go 0.8fr / 1.2fr with a sticky heading column and the quote link right-aligned in each row; steps become three columns; town names flow inline instead of stacking.

Lists are ruled, not boxed: rows of 1.5rem vertical padding (2rem for the lead row) separated by 1px waterline hairlines, opened by a 2px ink rule. On phones hero buttons stack full width (max 26rem) with a 0.75rem gap, and the body reserves 5.5rem plus safe-area inset at the bottom for the sticky bar.

## Elevation & Depth

Mostly flat with tonal banding. Depth comes from the world's materials (the foam bank, glass bubbles, beading) and from soft, tinted shadows under the gold and the bubbles; no surface is lifted as a card. Layering inside the hero is fixed: photo bubbles and loose bubbles at the back (z 0), the foam canvas over them (z 1), the copy and freed bubbles on top (z 2).

### Shadow Vocabulary
- **Gold lift** (`box-shadow: 0 1px 0 rgba(255,255,255,.55) inset, 0 6px 18px -6px rgba(133,96,15,.55)`): primary button at rest; deepens to `0 10px 24px -8px` on hover with a 1px rise.
- **Logo ring** (`box-shadow: 0 0 0 2px gold, 0 4px 10px -4px rgba(20,23,26,.5)`): the 44px logo in the top bar and footer.
- **Bubble contact** (`box-shadow: 0 0 0 1px rgba(255,255,255,.75), 0 12px 20px -14px rgba(15,74,114,.4)`): a white hairline rim and a faint navy contact shadow under each photo bubble.
- **Glass wall** (stacked insets: 1.5px white at .95, then 3px cyan, 4.5px magenta, 6px gold film at .38/.22/.14, plus `inset 0 -20px 34px -12px rgba(21,90,136,.32)`): the soap-film wall drawn over each photo.
- **Sticky veil** (`box-shadow: 0 -8px 24px -12px rgba(15,74,114,.25)` with `backdrop-filter: saturate(1.4) blur(12px)`): the mobile booking bar.
- **Bead** (inset dark bottom, inset light top, 2-3px outer drop in deep rinse): water drops on the rinse band.
- **Foam surface** (canvas shadow rgba(79,125,158,.4), 14px blur, -2px offset): the soft upward shadow along the foam bank's crest.

### Named Rules
**The Tinted Shadow Rule.** Shadows are tinted by what casts them: gold-brown under gold, rinse-navy under bubbles, foam, and the sticky bar. No neutral grey drop shadows and no hard offset shadows.

**The Press Flattens Rule.** Pressing any button removes its shadow and lift and inverts it to ink with gold-bright text.

## Shapes

Only two silhouettes: the pill (999px) for buttons and the circle for the logo, photo bubbles, foam and loose bubbles, dot marks, town dots, the sticky call button, and water beads (slightly flattened, 50% 50% 48% 48% / 46% 46% 54% 54%). Everything else is unbounded: sections are full-bleed bands, lists are ruled rows, and there are no cornered cards. Photography is only ever clipped to a circle. Borders are hairlines (1px waterline) or deliberate rules (2px ink top rule on the service list, 1.5px underline on quote links). Section joins are ripple seams: three stacked quadratic wave strokes, 1.5px non-scaling, 28px tall, drawn over a hard 50/50 split of the two adjoining band colors.

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
A ruled list, not a card grid. Each row: a solid gold dot (1.05rem; 1.35rem on the lead row), a title-weight service name, and a soft-ink description. The whole row is one link (an SMS pre-filled with that service), cued only by a 2.75rem circular arrow at the row's end: hairline ring and water-blue arrow at rest; on hover the circle fills water blue, the arrow turns white and nudges 3px, and the title turns rinse; on press it inverts to ink with gold-bright. Never repeat a text CTA label on every row; the section intro carries "tap a detail" once, and a visually hidden "text for a quote" keeps each link's accessible name complete. The lead row (the flagship service) gets more padding and a larger title.

### Step Numerals
Giant 900-weight rinse-blue numerals beside (phone) or above (desktop) a title and one sentence. They replace icons as the step marker.

### Town List
Town names in headline-scale uppercase white on the rinse band, each preceded by a gold-bright dot sized at 0.26em; a sentence-case rinse-haze line closes the list.

### Navigation
No menu. The header is the logo (44px circle with gold ring) plus uppercase wordmark, with the phone number (tabular figures, ink, water-blue on hover) appearing at 760px and up. The logo appears only here and in the footer.

### Sticky Booking Bar (mobile)
Fixed bottom bar below 760px: foam at 94% with blur, a hairline top border, a full-width gold primary, and a 3.5rem circular call button (white, 2px ink border, inverts on press). It slides out (0.45s) while the hero buttons are in view and returns once they scroll away.

### Photo Bubbles (signature)
The client's real work held as glass soap bubbles riding the foam: a large exterior shot (84% of the pair's square) at top right and a smaller interior shot (44%) overlapping it at lower left. Each is a circle-clipped photo with the glass wall and bubble contact shadows, a soft wet-light sheen (a faint low ellipse plus a bright band at the rim's last 16%), and a window highlight: a white 3px arc (2px on the small bubble) hugging the upper-left wall, masked to fade along the curve. The two bob on alternating 8s and 6.5s cycles (4px across, 12px up, 1.2deg). They sit under the foam so suds lap their base, and pause when the hero is off screen. Photos are real, sourced client images with provenance embedded; never stock, never a full-bleed background.

### Foam Bank (signature)
A live canvas across the bottom of the hero. Thousands of pre-rendered shaded bubble sprites are packed edge to edge, largest at the surface and shrinking with depth (scaled 1.3x below 600px); walls whiten through four depth levels (#a8bfd0 to #e9f0f5) and three highlight variants keep the field from tiling. The surface is a rolling multi-sine crest with a soft upward shadow, depth lanes slide at their own speeds in a shear current, surface bubbles occasionally pop and re-form deeper, and the bottom thickens into a cream fade that meets the foam page ground. It settles on load, pauses off screen, and renders one still frame under reduced motion.

Interactive: a mouse or finger pushes and drags nearby suds, which spring back with a wobble; a resting pointer dips the surface; fast swipes pop bubbles; and a bubble pushed above the liquid line breaks free into a loose floating bubble (capped at 40). Touch listeners are passive so scrolling is never blocked.

### Loose Bubbles
Small glass bubbles (10-38px) rise steadily out of the foam bank (6 on phones, 11 on larger screens), swaying side to side over 6-12s and popping with a brief swell at the top. Each is a near-clear disc with a bright top-left highlight and a whitening rim. Off under reduced motion; paused off screen.

### Water Beading (signature)
About 70 flattened, rinse-tinted domes clustered in the rinse band's top-right, masked to fade out; on phones they collapse to a thin strip along the top edge.

## Do's and Don'ts

### Do:
- **Do** keep every ground cool and light (foam, mist), with rinse blue as the single saturated band.
- **Do** reserve gold for the primary action, dot marks, focus/selection, the logo ring, and the gold-ink word BLESSED.
- **Do** set every H1/H2 in 900-weight uppercase with -0.03 to -0.035em tracking.
- **Do** present offerings as ruled rows with dot marks and lists of big type, not boxed cards.
- **Do** show real client work only inside soap-bubble frames, layered beneath the foam so the suds lap the base.
- **Do** join bands with ripple seams drawn over a 50/50 split of the adjoining colors, at 0.35 stroke opacity in water blue or 0.75 in spray blue next to rinse.
- **Do** make the primary action a gold pill with ink text, and invert every button to ink with gold-bright text on press.
- **Do** keep the booking action one thumb away on phones via the sticky bar, hidden while the hero CTAs are visible.
- **Do** keep every moving material paused off screen, and honor reduced motion: the foam renders one still frame, bubbles stop bobbing, loose bubbles and smooth scroll switch off.
- **Do** keep pointer and touch interaction passive: it may stir the foam but never blocks scrolling.

### Don't:
- **Don't** use a dark hero over a car photo, a full-bleed photo background, or a grid of icon cards.
- **Don't** put photos in cornered frames or cards; photography is clipped to a bubble or not shown.
- **Don't** use gold for large fields, step numbers, headline accents, links, or secondary buttons.
- **Don't** set gold-bright or gold as text on foam or mist; use gold-ink.
- **Don't** add ornament outside the world's materials (foam, glass bubbles, water beading, ripple seams).
- **Don't** introduce cornered cards, square buttons, or hard offset shadows.
