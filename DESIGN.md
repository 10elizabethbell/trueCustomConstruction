---
name: True Custom Construction LLC
description: A yard crew's one-page site built as a soil cutaway under an overcast sky.
colors:
  yellow: "#F2B417"
  yellow-deep: "#DDA00A"
  cedar: "#9A5226"
  focus: "#2F6FB0"
  sky-top: "#C4D6E0"
  sky-low: "#E9EAE4"
  ground: "#ECEDE9"
  ground-2: "#DFE2DD"
  slate: "#22303A"
  slate-2: "#2C3C48"
  ink: "#1F2B33"
  ink-soft: "#4A5763"
  on-slate: "#EEF1F2"
  on-slate-soft: "#BAC5CD"
  topsoil: "#5E4129"
  clay: "#A4774C"
  turf: "#4E8A3A"
  field: "#FBFCFA"
  field-stroke: "#8C958F"
  rule: "#C5CBC6"
  rule-on-slate: "#3A4B57"
  error: "#A3261B"
  placeholder: "#5F6970"
  hint-on-soil: "#FBF3E8"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(44px, 12.4vw, 96px)"
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(34px, 8vw, 64px)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.01em"
  row:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(25px, 6.6vw, 34px)"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 900
    lineHeight: 1.15
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 2vw, 20px)"
    fontWeight: 400
    lineHeight: 1.45
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1.2
  numeral:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "40px"
    fontWeight: 900
    lineHeight: 0.9
  panel-title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 900
    lineHeight: 1
  wordmark:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "21px"
    fontWeight: 900
    lineHeight: 1
  wordmark-sub:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "11px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.2em"
  hint:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 800
    lineHeight: 1.4
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 600
    lineHeight: 1.4
rounded:
  focus: "4px"
  control: "10px"
  photo: "8px"
  pill: "50%"
spacing:
  gutter-phone: "20px"
  gutter: "32px"
  stack: "22px"
  section-phone: "56px"
  section-desk: "88px"
  gallery-gap: "10px"
components:
  button-primary:
    backgroundColor: "{colors.yellow}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.yellow-deep}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0 22px"
    height: "56px"
  button-ghost-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.ground}"
  button-ghost-on-slate:
    backgroundColor: "transparent"
    textColor: "{colors.on-slate}"
  button-ghost-on-slate-hover:
    backgroundColor: "{colors.on-slate}"
    textColor: "{colors.slate}"
  service-row-arrow:
    backgroundColor: "{colors.ground-2}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "46px"
  service-row-arrow-hover:
    backgroundColor: "{colors.yellow}"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "14px"
    height: "54px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "0 16px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.ground}"
  ready-panel:
    backgroundColor: "{colors.ground-2}"
    rounded: "{rounded.control}"
    padding: "20px"
---

# Design System: True Custom Construction LLC

## Overview

**Creative North Star: "The Soil Cutaway"**

The site is a cross-section of a job: overcast sky on top, topsoil over rocky clay below, a dark board-and-batten wall at the edge, and the crew's yellow tracked skid steer doing the work. Every page surface borrows from that cutaway. Light limestone-concrete ground carries the reading sections; charcoal-blue slate, the color of the house siding, carries the photo and closing sections; strips of live sod over a soil band stitch one to the other.

The type is a plain system sans, set heavy and uppercase for anything that names a thing, sentence-case for everything a person reads. Surfaces are flat. Depth comes only from the canvas scenes and from color blocks changing under a sod edge. Yellow is the machine's color and the primary action's color, nothing else.

Density is phone-first and generous: 56px tap targets, full-width stacked buttons on phones, one column until 1024px.

**Key Characteristics:**
- Two grounds only: light concrete and charcoal-blue slate, alternating, joined by sod strips.
- Heavy uppercase system-sans display; sentence-case body.
- Construction yellow reserved for the primary action and the machine.
- Flat surfaces; no shadows except focus halos and the canvas machine's ground shadow.
- Two canvas scenes (hero yard, sod strips) carry the world; everything else is quiet.

## Colors

An earth-and-weather palette: neutral concrete and siding blue-grey, one hot yellow, soil browns and turf green confined to the drawn scenes.

### Primary
- **Construction Yellow** (yellow): primary button fill, the skid steer's body, `::selection`, hovered service-row arrow. Deepens to **Worn Yellow** (yellow-deep) on hover.

### Secondary
- **Cedar** (cedar): the numerals in "How it goes" only. The house's cedar trim; it marks sequence, never action.

### Tertiary
- **Water Blue** (focus): every focus outline, input and chip hover/focus border, and the 3px focus halo at 25% alpha. It is also the puddle and runoff color in the yard canvas (drawn as rgba(70,122,165,.85)), so "blue means water and attention."

### Neutral
- **Overcast Sky** (sky-top to sky-low): hero gradient, top to 62%; sky-top is also the browser theme color.
- **Concrete Ground** (ground): page background and light section ground.
- **Poured Concrete** (ground-2): resting service-row arrow, ready-to-send panel.
- **Siding Slate** (slate): dark sections (Our work, Close, footer). **Slate Raised** (slate-2) fills empty gallery frames.
- **Ink** (ink) / **Ink Soft** (ink-soft): text on light ground; soft for ledes, step copy, optional markers, wordmark subline.
- **On-Slate** (on-slate) / **On-Slate Soft** (on-slate-soft): text on slate; soft for close copy and footer.
- **Field** (field) / **Field Stroke** (field-stroke): input and chip fill and 2px resting border.
- **Rule** (rule): 1px hairlines between service rows. **Rule on Slate** (rule-on-slate): footer top border.
- **Error Red** (error): field error text and invalid border.

### World colors (canvas only)
- **Topsoil** (topsoil): soil band in every sod strip and the yard's surface layer. **Clay** (clay): the static no-JS yard fallback. **Turf** (turf): middle of the three-green blade set (#3F7A2E / #4E8A3A / #5E9A44 in the yard, #62A047 as the light blade in sod strips).

### Named Rules
**The Machine Yellow Rule.** Yellow is the machine and the primary action. It never becomes a background band, a heading color, or decoration.

**The Two Grounds Rule.** A section is either concrete (ground) or slate. No third section color, and no black page ground.

**The Soil Stays Underground Rule.** Topsoil, clay, and turf live inside canvas scenes and sod strips. They don't fill UI components.

## Typography

**Display Font:** system sans stack (-apple-system, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** same stack

**Character:** One family, two voices. Black-weight (900) uppercase with slightly tight tracking (-0.01em) for names of things; regular sentence case for speech. The system stack is a deliberate house style: native and fast in Facebook's in-app browser, and it reads like painted lettering on a work truck.

### Hierarchy
- **Display** (900, clamp 44-96px, 0.92, uppercase, max 11ch): the hero headline only.
- **Headline** (900, clamp 34-64px, 1.0, uppercase): every section h2.
- **Row** (900, clamp 25-34px, 1.05, uppercase): service rows. These are links styled as large type.
- **Title** (900, 20-22px, 1.15, uppercase): step titles, the ready panel heading.
- **Numeral** (900, 40px, 0.9, cedar): step numbers.
- **Lede** (400, clamp 17-20px, 1.45, ink-soft or on-slate-soft, 36-40ch): the hero promise, quote lede, close copy.
- **Body** (400, 17px, 1.55): default text.
- **Label** (800, 16-17px): buttons, form labels, legends, the header phone link. Chips use 700; optional markers use 500 in ink-soft.

### Named Rules
**The Names Shout, Sentences Talk Rule.** Uppercase 900 is for h1-h3, service rows, and the wordmark. Paragraphs, labels, buttons, and errors stay sentence case.

**The Balanced Heading Rule.** All headings use `text-wrap: balance` and line-height of 1 or less.

## Layout

A single centered column, max width 1180px, with a gutter of 20px on phones and 32px from 640px up. Sections stack vertically. Light sections are padded 56px top / 64px bottom on phones and 88px / 96px from 1024px. Slate sections use their own padding (work 40/64, close 48/40).

- **Phone (<640px):** everything stacks. Buttons are full width and capped at 440px. The gallery is a 2-column grid; the lead photo spans both columns.
- **640px+:** hero buttons sit side by side at auto width; the gallery goes to 3 columns.
- **1024px+:** services and steps sit side by side (1.1fr / 1fr, 88px gap). The gallery goes to 4 columns with 300px rows, and the lead photo spans 2x2. The quote column caps at 760px. The footer becomes a 3-part row. The hero yard canvas moves behind the copy (see Components).
- **Rhythm:** about 22px from a heading to its content; 10-14px between sibling controls; 26px between steps and before the gallery.
- **Safe areas:** the viewport uses `viewport-fit=cover`, and the footer pads by `env(safe-area-inset-bottom)`.

## Elevation & Depth

Flat. No surface has a resting shadow. Depth comes from the drawn scenes (soil strata, the house wall, the machine with a soft ellipse shadow at rgba(40,26,14,.28)) and from a section's color changing under a sod edge.

### Shadow Vocabulary
- **Focus halo** (`box-shadow: 0 0 0 3px rgba(47,111,176,.25)`): inputs on focus, chips on keyboard focus, form buttons on hover/focus. A state signal, not elevation.
- **Scene-text glow** (`text-shadow: 0 0 6px #4A3220, 0 0 14px #4A3220, 0 1px 2px #3A2616`): only for text set directly on the soil canvas (the yard hint). It is soil-colored, not an accent.

### Named Rules
**The Flat Surface Rule.** UI is flat at rest. Shadows mean focus, or they belong to the drawn world.

## Shapes

One gentle radius (10px) for every control and panel: buttons, inputs, chips, the ready panel. Photos use a slightly tighter 8px with overflow clipped. The only circle is the 46px service-row arrow. Borders are 2px on controls (ink, yellow, field-stroke, or on-slate) and 1px for hairline rules. The global focus outline is 3px solid water blue at 3px offset with a 4px radius.

The one organic silhouette is the sod edge: a wavy soil line (two summed sines) with grass blades above. Everything else is rectilinear.

## Components

### Buttons
Big, flat, full-bleed on phones.
- **Shape:** 10px radius, 2px ink border, min-height 56px, 22px side padding, 800 weight, optional 22px leading inline SVG.
- **Primary:** yellow fill, ink text, ink border. Hover: yellow-deep.
- **Ghost:** transparent with an ink border; inverts to an ink fill with ground-colored text on hover.
- **On slate:** primary keeps a yellow border; ghost becomes on-slate text and border and inverts to on-slate fill with slate text.
- **In forms:** hover/focus adds a water-blue border and the focus halo.
- **Transition:** background, color, and border at .18s ease-out. Removed under reduced motion.

### Service rows
The service list is a stack of big uppercase links between 1px rule hairlines, min-height 76px. Each row ends in a 46px round arrow chip (ground-2) that turns yellow on hover/focus. Row hover never adds a background; only the arrow responds. Keyboard focus outlines the arrow, not the row. Clicking a row preselects the matching job chip in the quote form.

### Steps
A two-column grid (44px numeral column). The 900-weight cedar numeral spans the title and body lines; titles use the uppercase Title style; body text is ink-soft.

### Chips
- **Style:** visually hidden radio and a visible span. Min-height 48px, 16px padding, 2px field-stroke border, field fill, 700 weight, 10px radius.
- **State:** hover gives a water-blue border; keyboard focus adds the halo; selected becomes an ink fill with ground text. A selected chip that is hovered or focused gets a water-blue border.

### Inputs / Fields
- **Style:** field fill, 2px field-stroke border, 10px radius, 14px padding, min-height 54px (textarea 120px, vertical resize), 16px text so iOS doesn't zoom. Placeholder #5F6970.
- **Hover / Focus:** water-blue border; focus adds the halo, with no outline.
- **Error:** error-red border and a 15px/600 error message below. The message is hidden when empty, and it clears on input.
- **Labels:** 800 weight above the field. "(optional)" is marked in 500 ink-soft.

### Ready panel
The form hands off to a ground-2 panel (10px radius, 20px padding) holding a read-only composed message and two stacked buttons. When BIZ.PHONE is set, the send button becomes an SMS link; otherwise it opens Messenger and copies the message to the clipboard.

### Header
A minimal top bar with no nav. The wordmark is two lines: "True Custom" in 900 uppercase at 21px over "Construction LLC" in 700 uppercase at 11px, tracked .2em, in ink-soft. This is a logo lockup, not a reusable label style. A phone slot sits on the right: a muted "Phone coming soon" (600, 14px) until BIZ.PHONE is set, then an 800-weight tel: link. The footer phone appears the same way.

### Sod strip divider (signature)
A 46px band (56px at 1024px+) placed between sections of different ground. The canvas draws a wavy topsoil band, 11px thick, over the next section's color, read live from `--slate` or `--ground` via `data-sod`. The strip's own background matches the section above. About W/2.4 blades in three greens, clumped by a low-frequency "lushness" field, sway on two sines and spring away from a nearby pointer (spring 38, damping 6.5). A variant (`gallery-turf`, 9px band, transparent background) overlaps the bottom of the gallery by 26px so the photos stand on turf. Strips are `aria-hidden`, ignore pointer events, and draw one static frame under reduced motion.

### Hero yard canvas (signature)
An interactive soil cutaway that fills the bottom of the hero. Drag (touch) or hover-move (mouse) to drive the skid steer: its bucket levels lumps, flung dirt crumbs arc off, sod grows back on graded columns, and rain runs off the new slope instead of pooling at the foundation. The scene shows topsoil over a gradient clay body with a rocky band and stones, a board-and-batten wall with a concrete foundation and downspout, and on wide screens a window, eave, and gutter. When no one is driving, a ghost path drives itself. A finished lawn holds for RESET_AFTER seconds, then cross-fades to a new yard.
- **Tunables (the `T` object):** STEP_PHONE / STEP_DESK (px per ground column, 4/3), ROUGH, GRADE_RATE 6.5, GRADE_OK 2.2px, GRASS_RATE .55, GRASS_LOSS 2.4, RAIN 13 drops/s per 100px, DROP_VOL, INFIL, INFIL_GRASS, MACHINE_SPEED_PHONE/DESK 190/300, RESET_AFTER 13s, USER_IDLE 9s. Tune the feel here, not in the draw code.
- **Responsive:** below 640px ("phoneish") it uses a 58px wall, machine scale 1.1, and smaller lumps. At 1024px and up ("flip") the canvas goes full-bleed behind the hero copy and the whole scene is mirrored, so the house sits on the right and the copy keeps the left. The wall widens to 21% of width (230-380px). The ground line drops below the buttons, and rain spawns below the copy block so it never streaks across the text. Copy stays clickable through `pointer-events` passthrough. Machine scale is 1.25 below 1100px and 1.5 above. DPR is capped at 1.5.
- **Hint:** "Drag to drive the skid steer" (or "Move across the yard…" for fine pointers). 15px/800 cream on the soil, using the scene-text glow. It sits bottom-right on phones and bottom-left on desktop, and fades on first input.
- **Fallbacks:** without JS, a CSS gradient still shows topsoil and clay bands. Under reduced motion, one static frame is drawn and the hint is removed. Both canvases pause offscreen through a shared IntersectionObserver loop.
- **BIZ.PHONE:** one config switch. Empty means the header shows "Phone coming soon", the footer hides the number, and the form hands off to Messenger. Filled means tel: links in the header and footer and an SMS hand-off.

## Do's and Don'ts

### Do:
- **Do** alternate concrete and slate sections and put a sod strip at every change (`sod--to-slate` on ground, `sod--to-ground` on slate).
- **Do** keep every control at least 48px tall (buttons 56px, inputs 54px, chips 48px), with tap targets of 44px or more for links.
- **Do** use water blue for every focus and hover-to-edit signal: a 3px outline, or a border plus the 25% halo.
- **Do** keep canvas tuning in `T` and business facts in `BIZ`. Read section colors from `:root` tokens, not literals.
- **Do** give every canvas a reduced-motion still frame and a no-JS fallback.

### Don't:
- **Don't** use yellow for anything but the primary action and the machine.
- **Don't** add resting shadows, gradients on UI surfaces, or a third section color. Don't use a black page ground.
- **Don't** set body copy, buttons, or labels in uppercase. Uppercase 900 is for names: headings, rows, the wordmark.
- **Don't** reuse the wordmark's tracked small-caps subline as a section label or eyebrow above headings.
- **Don't** add hover backgrounds to service rows; the arrow is the only affordance.
- **Don't** put rain, glare, or animated elements over the hero copy column on desktop.
