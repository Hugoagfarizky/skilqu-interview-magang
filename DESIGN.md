---
name: Skilqu
description: Cheat sheet interview magang gratis; Soft Cards on a pale sky ground.
colors:
  interview-blue: "#1d5bd0"
  action-amber: "#f59e0b"
  action-ink: "#1f1400"
  amber-edge: "#d98706"
  stamp-ink: "#9a4a06"
  stamp-paper: "#fffbeb"
  ink: "#0f2a4a"
  muted: "#47607e"
  sky-ground: "#f3f9ff"
  sky-tint: "#e6f3ff"
  hairline: "#d6e6f7"
  surface: "#ffffff"
  success-green: "#1d6b3f"
typography:
  display:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "clamp(36px, 3.4vw + 8px, 60px)"
    fontWeight: 800
    lineHeight: 1.06
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "clamp(30px, 1.72vw + 23.3px, 48px)"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "-0.03em"
  statement:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "clamp(28px, 2.2vw + 14px, 46px)"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 800
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  price:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "34px"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  lead:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    lineHeight: 1.4
  small:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  check: "8px"
  tile: "10px"
  stamp: "12px"
  input: "14px"
  chip: "16px"
  card: "22px"
  pill: "999px"
spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "32px"
  xl: "48px"
  section: "64px"
  section-max: "96px"
components:
  button-primary:
    backgroundColor: "{colors.action-amber}"
    textColor: "{colors.action-ink}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "44px"
  button-primary-hero:
    backgroundColor: "{colors.action-amber}"
    textColor: "{colors.action-ink}"
    rounded: "{rounded.pill}"
    padding: "0 28px"
    height: "56px"
  input-email:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.input}"
    padding: "0 18px"
    height: "56px"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "28px"
  flow-pill:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.muted}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "8px 14px"
  flow-pill-active:
    backgroundColor: "{colors.interview-blue}"
    textColor: "{colors.surface}"
    rounded: "{rounded.pill}"
    padding: "8px 14px"
  star-letter:
    backgroundColor: "{colors.sky-tint}"
    textColor: "{colors.interview-blue}"
    rounded: "{rounded.tile}"
    size: "34px"
  stamp:
    backgroundColor: "{colors.stamp-paper}"
    textColor: "{colors.stamp-ink}"
    rounded: "{rounded.stamp}"
    padding: "8px 14px"
  tag-soon:
    backgroundColor: "{colors.sky-tint}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "2px 10px"
---

# Design System: Skilqu

## Overview

**Creative North Star: "The Filled-In Cheat Sheet"**

The product's own content is the hero: a white cheat-sheet card with its S, T, A, R rows filling in, laid on a pale sky ground. Everything else on the page is the same material, white soft-cornered cards floating on light blue, so a visitor reads one calm, studious surface rather than a marketing collage. Density is relaxed; type is large and heavy enough to read on a phone at arm's length.

Blue is the voice of the method (the STAR letters, key words, the active step); amber is reserved for one thing, taking the free kit, plus the "Siap interview" stamp that marks the payoff. Depth comes from a long, soft, bluish shadow under every card, never from borders or hard offsets. Motion is small and purposeful: loops that demonstrate the method a few times and then rest.

**Key Characteristics:**
- Pale sky ground with a top-to-bottom hero gradient into a slightly deeper sky tint.
- White cards, large radius (22px), soft bluish ambient shadow.
- One typeface (Plus Jakarta Sans) carrying everything; display at 800 with tight tracking.
- Interview blue for the method, amber only for the action and the stamp.
- One-weight line SVG icons, drawn with currentColor.
- Motion that demonstrates, then rests; fully still under reduced motion.

## Colors

A cool, airy blue world with a single warm signal.

### Primary
- **Interview Blue** (interview-blue): the method's colour. STAR letter text, highlighted words in headings, the active flow pill, checklist ticks and progress bar, the "Skilqu" column header in the comparison table, the free-plan card's outline, inline line icons, and focus rings on inputs and STAR rows.

### Secondary
- **Action Amber** (action-amber): the primary button fill, with a darker amber edge (amber-edge) and a warm glow shadow. Also the stamp's 3px border. Nowhere else.
- **Action Ink** (action-ink): label colour on amber buttons.
- **Stamp Ink / Stamp Paper** (stamp-ink on stamp-paper): the "Siap interview" stamp only.

### Neutral
- **Deep Navy Ink** (ink): headings, body, table text; also the global focus outline.
- **Slate Muted** (muted): sub-labels, captions, inactive pills, price suffixes, reassurance lines.
- **Sky Ground** (sky-ground): page background and the hero gradient's top stop.
- **Sky Tint** (sky-tint): hero gradient's bottom stop, icon and STAR-letter tiles, the progress-bar track, picked STAR row, "segera hadir" tag.
- **Hairline Sky** (hairline): row dividers inside cards, input and pill borders, table rules.
- **Card White** (surface): every card, input, chip and inactive pill.
- **Proof Green** (success-green): "yes" ticks in the comparison table and the "Jawaban STAR" tag. A semantic colour, not decoration.

### Named Rules
**The One Warm Thing Rule.** Amber means "take the free kit" (and the stamp that rewards it). If something amber is not the action or the stamp, it is wrong.

**The Blue Is The Method Rule.** Interview Blue marks the STAR structure and the words that matter. It is not a background for sections or a second button colour.

## Typography

**Display Font:** Plus Jakarta Sans (with system-ui, sans-serif)
**Body Font:** Plus Jakarta Sans (with system-ui, sans-serif)

**Character:** A single friendly geometric sans, user-chosen, doing all the work through weight: 800 for headings, 600 for labels, 400 for reading.

### Hierarchy
- **Display** (800, clamp 36px to 60px, 1.06, -0.03em): the hero H1 only; 31px on phones. Key words take Interview Blue.
- **Headline** (800, clamp 30px to 48px, 1.1, -0.03em): section headings.
- **Statement** (700, clamp 28px to 46px, 1.3, -0.02em, max 26ch): the single scroll-highlighted statement line.
- **Title** (800, 20px, 1.3, -0.01em): card and FAQ-adjacent titles (h3); h4 in the kit list at 16px 800.
- **Price** (800, 34px, -0.02em): plan prices; the suffix drops to 16px 600 muted.
- **Lead** (400, 18px, 1.5): hero sub-headline and closing line.
- **Body** (400, 16px, 1.55): all reading text; STAR rows at 15px, 1.5.
- **Label** (600, 15px): form labels, flow pills, card tags; STAR sub-labels at 13px 600 muted.
- **Small** (400, 14px): reassurance lines, fact captions.

Numbers that count or tick use tabular figures; hero fact values sit at 22px 800.

### Named Rules
**The One Family Rule.** Plus Jakarta Sans for every role. Hierarchy comes from weight and size, never from a second face.

## Layout

A 12-column grid in a 1280px container with 80px side gutters on desktop (48px tablet, 24px phone). The hero splits 7/5: copy, flow pills, email form and facts on the left, the cheat-sheet stage on the right. Sections pad clamp(64px, 7vw, 96px) top and bottom; heading-to-content gap is 64px in two-group sections. Spacing follows a 4/8 scale (8, 16, 24, 32, 48, 64, 96).

Breakpoints at 1023px and 639px. At 1023px and below the hero stacks (text and form first, card below), three-up grids go to one column, and the floating question chip hides. At 639px the email row stacks with a full-width button, card padding drops to 20px, and a sticky bottom action bar carries the primary button.

## Elevation & Depth

A lifted, soft-card system. Every card shares one ambient shadow with a long, bluish falloff; nothing uses hard or offset shadows. Layering inside the hero stage (sheet, then chip, then stamp) is done with z-order and the same soft shadow, not with stronger shadows.

### Shadow Vocabulary
- **Soft Card** (`box-shadow: 0 24px 48px -28px rgba(15, 42, 74, .35), 0 2px 6px -2px rgba(15, 42, 74, .08)`): every card, the cheat sheet, the question chip, the comparison table wrapper, the form card.
- **Amber Glow** (`box-shadow: 0 10px 22px -12px rgba(194, 120, 3, .9)`): primary buttons only.

### Named Rules
**The One Shadow Rule.** Cards lift with the Soft Card shadow and nothing else. Depth never escalates to signal importance; amber does that.

## Shapes

Generous, friendly rounding. Cards at 22px, chips at 16px, inputs at 14px, the stamp at 12px, icon and STAR tiles at 10 to 12px, checkboxes at 8px; buttons, flow pills, tags and the progress bar are full pills. Dividers inside cards are 1px Hairline Sky; the cheat-sheet preview header takes a 2px ink rule and dashed hairline rows, echoing printed paper. The stamp is the one tilted object (rotated -8deg).

## Components

### Buttons
- **Shape:** full pill (999px).
- **Primary:** Action Amber fill, Action Ink label, 1px amber edge, Amber Glow shadow. 44px in the nav, 56px with 0 28px padding and 17px label in the hero form, full width in the closing form and phone action bar.
- **Hover / Focus:** lifts 1px and lightens slightly toward the ground; press sinks 1px and scales to .985. Focus is a 2px ink outline offset 3px.
- **Secondary:** none; the page has one action.

### Chips
- **Flow pills:** white with hairline border and muted label; the active step fills Interview Blue with white text.
- **Question chip:** white, 16px radius, Soft Card shadow, sky-tint icon tile, floats over the sheet's corner (hidden below 1024px).
- **"Segera hadir" tag:** sky-tint pill, 13px 600, marks features not yet available.

### Cards / Containers
- **Corner Style:** 22px.
- **Background:** Card White on the sky ground.
- **Shadow Strategy:** Soft Card (see Elevation).
- **Border:** none visible; the free plan card takes a 2px Interview Blue outline to mark it as the offer.
- **Internal Padding:** 28px (24px for compact cards, 20px on phones).

### Inputs / Fields
- **Style:** white, 1.5px hairline border, 14px radius, 56px tall in the hero, 500 17px text. Closing-form fields follow the kit's field style inside the white form card.
- **Focus:** 2px Interview Blue outline offset 2px.
- **Error:** inline message under the field.

### Navigation
- Logo wordmark at 800 with an initial mark on the left, one primary button on the right. No menu links.

### STAR Rows (signature)
Each row is a 34px sky-tint tile carrying the letter in Interview Blue 800, beside a muted 13px sub-label and the answer line, separated by hairlines. In the hero the rows fill in one by one (unfilled rows at 18% opacity), the flow pills advance, and the stamp drops in scaled from 1.25; the loop runs three rounds then rests fully filled, and pauses on hover. In the solution card each row is a button: picking one dims the others to 35% and tints the picked row sky.

### Siap Interview Stamp (signature)
A tilted label (-8deg) with a 3px amber border, stamp-paper fill, stamp-ink 19px 800 text and a check icon. It marks completion only.

### STAR Checklist
White card with a tabular "n/4" counter in blue, an 8px sky track filling blue, and four rounded checkboxes that fill Interview Blue. Once in view it ticks from 0/4 to 4/4 once (450ms apart) and stays.

### Motion
One ease-out (`cubic-bezier(.2, .8, .2, 1)`), state transitions around 180 to 350ms. Demonstrative motion (hero loop, checklist, word-highlight statement, 100+ count) plays a bounded number of times and rests. Under prefers-reduced-motion everything renders in its finished state.

## Do's and Don'ts

### Do:
- **Do** set every surface as a white 22px card with the Soft Card shadow on the sky ground.
- **Do** keep amber to the primary action and the "Siap interview" stamp.
- **Do** use Interview Blue for STAR letters, key words, the active step, ticks and focus on inputs.
- **Do** draw icons as single-weight line SVGs in currentColor, sized 14 to 22px, inside sky-tint tiles where they need a container.
- **Do** let looping motion finish and rest, and render the finished state under reduced motion.
- **Do** show the product's real content (cheat-sheet rows, answers) instead of abstract feature icons.

### Don't:
- **Don't** add a second button colour or a secondary button style; there is one action.
- **Don't** use hard, offset or dark shadows; depth is the one soft bluish shadow.
- **Don't** introduce a second typeface for display or labels.
- **Don't** use emoji or filled/glyph icons.
- **Don't** fill whole sections with Interview Blue or amber; colour stays on small marks against white and sky.
