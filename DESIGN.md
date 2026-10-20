---
name: True Custom Construction LLC
description: A grading-and-remodel crew's one-page site in calm full-bleed bands of paper, slate navy and deep slate, with one Cat-machine yellow.
colors:
  yellow: "#f5bf1d"
  yellow-2: "#ffd04d"
  yellow-ink: "#7d5800"
  navy: "#22384f"
  deep: "#142233"
  focus: "#2f5f93"
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  figure-ground: "#dfe5ee"
  ink: "#142233"
  body: "#2a3747"
  soft: "#4b5868"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c8d3e0"
  line: "rgba(20,34,51,.12)"
  error: "#b3261e"
  facebook-blue: "#1877f2"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(44px, 12.4vw, 84px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  display-wide:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(52px, 7.2vw, 84px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  row:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(24px, 6.6vw, 30px)"
    fontWeight: 400
    lineHeight: 1.1
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  eyebrow:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
  wordmark-sub:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "11px"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.08em"
  scale:
    s11: "11px"
    s14: "14px"
    s15: "15px"
    s16: "16px"
    s17: "17px"
    s18: "18px"
    s19: "19px"
    s20: "20px"
    s21: "21px"
    s22: "22px"
    s24: "24px"
    s30: "30px"
    s44: "44px"
    s48: "48px"
    s52: "52px"
    s84: "84px"
rounded:
  focus: "6px"
  field: "10px"
  fb-row: "20px"
  card: "24px"
  circle: "50%"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  stack-sm: "12px"
  stack-md: "16px"
  stack-lg: "20px"
  stack-xl: "28px"
  card-pad: "clamp(20px, 5vw, 32px)"
  band: "64px"
  band-wide: "96px"
components:
  button-primary:
    backgroundColor: "{colors.yellow}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.yellow-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  eyebrow:
    backgroundColor: "rgba(20,34,51,.06)"
    textColor: "{colors.ink}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  eyebrow-on-dark:
    backgroundColor: "rgba(255,255,255,.12)"
    textColor: "{colors.on-dark}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.row}"
    padding: "12px 0"
    height: "76px"
  arrow-circle:
    backgroundColor: "rgba(20,34,51,.07)"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  arrow-circle-hover:
    backgroundColor: "{colors.yellow}"
    textColor: "{colors.ink}"
  step-number:
    backgroundColor: "{colors.yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "48px"
  work-figure:
    backgroundColor: "{colors.figure-ground}"
    rounded: "{rounded.card}"
  fb-row:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.fb-row}"
    padding: "14px 16px 14px 22px"
    height: "76px"
  form-card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.body}"
    rounded: "{rounded.card}"
    padding: "{spacing.card-pad}"
    width: "600px"
  input-field:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  header:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    height: "64px"
  footer:
    backgroundColor: "{colors.deep}"
    textColor: "{colors.on-dark-soft}"
    padding: "48px 0 96px"
  float-circle:
    backgroundColor: "{colors.yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "60px"
---

# Design System: True Custom Construction LLC

## Overview

**Creative North Star: "The Crew's Own Yard"**

The site is the crew's own world laid out in calm, full-bleed bands: off-white paper, the slate navy and deep slate of the dark board-and-batten house on their Facebook profile, and one warm yellow taken from the Cat 279D loader in their job video. It is Ellie's calm band style (after lpmr.co.uk) applied to a grading-and-remodel crew. Bands alternate light and dark so each section begins plainly, and the only photograph that leads is their own machine on a yard they graded.

Density is low and phone-first. Each band holds one heading, one short idea, and at most one action group. Shapes are soft and borderless: 24px cards, full pills, tinted fields with no stroke. Depth comes from the bands and from tint, not from shadow; only two things lift off the page, the Facebook row and the floating message circle.

Motion is limited to three moves. The hero H1 bounces in letter by letter. Everything that starts below the first screen fades up 12px. The message circle slides in once the hero has gone. All three switch off under reduced motion.

**Key Characteristics:**
- Paper, two slate navies, one yellow. The ground is never black.
- Yellow is a fill. When yellow has to be text on a light ground it becomes Yellow Ink.
- One display face (Cal Sans, weight 400) for every heading, row, label and button. Body text is the system stack at 16/1.7.
- Soft, borderless forms: 24px cards, 999px pills, 10px tinted fields, 50% circles.
- On the service rows and the Facebook row, only the arrow circle reacts to hover.

## Colors

The palette is cool and quiet: a blue-tinted paper, two slate navies from the client's house, and one saturated machine yellow that carries every primary action.

### Primary
- **Cat-Machine Yellow** (yellow): the one warm accent. It fills primary buttons, step numbers, the eyebrow dot, the arrow circle on hover, the floating message circle and `::selection`. On dark bands and in the hero it is also the colour of the accent phrase and the focus ring. Text on it is always Slate Ink.
- **Lit Yellow** (yellow-2): primary-button hover fill only.
- **Yellow Ink** (yellow-ink): yellow used as text or icon on a light ground: the accent phrase on paper and the header phone icon and hover. It passes 4.5:1 on paper, which the yellow does not.

### Secondary
- **Board-and-Batten Navy** (navy): the hero band (under the photo on phones) and the quote-form band. It is also the input caret colour.
- **Deep Slate** (deep): the "How it goes" band and the footer, always with the faint 135° line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`).

### Tertiary
- **Field Blue** (focus): hover and focus outlines on form controls, and every focus ring on light grounds. It is kept apart from the yellow so a focused field never looks like a primary button.

### Neutral
- **Cool Paper** (paper): page ground, header, the light bands, and the theme colour.
- **Card White** (card): the form card, the ready panel, the Facebook row, the selected-chip text and the hero H1.
- **Field Tint** (field): inputs and unselected chips on the white form card. It is a separate token because paper on white is about 1.08:1 and fails non-text contrast.
- **Photo Ground** (figure-ground): what a work figure shows while its photo loads.
- **Slate Ink** (ink): headings and text on yellow. As translucent tints it also makes the eyebrow fill (6%), the arrow-circle rest fill (7%), the Facebook-row shadow (7%), the row dividers (12%), the line-button stroke (35%) and the hero overlay (40 to 86%).
- **Running Text** (body): paragraphs on light grounds.
- **Quiet Text** (soft): ledes, the wordmark sub-line, the "Phone coming soon" slot, field hints, placeholders and helper notes.
- **On Dark** (on-dark): headings, ghost-button text and footer links on navy and deep bands. At 70% it is the ghost-button stroke.
- **On Dark Soft** (on-dark-soft): running text on navy and deep bands.
- **Divider** (line): 1px rules between service rows.
- **Error Red** (error): inline error text and the bad-field border.
- **Facebook Blue** (facebook-blue): the Facebook glyph on the "see more of our work" row only. It is a brand mark, not a palette colour.

### Named Rules
**The Fill-Only Yellow Rule.** Yellow is never text on a light ground. Use it for fills and for accents on navy or deep slate; on paper or white the same role uses Yellow Ink.

**The Two Focus Colours Rule.** Focus rings are Field Blue on light grounds and Yellow on navy, deep slate, the hero and the footer. Form controls inside the navy band are back on a white card, so they use Field Blue.

**The Never-Black Rule.** The darkest ground is Deep Slate. No band, overlay or panel goes to black.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** the system stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** Cal Sans is a rounded, friendly geometric display face. At weight 400 and tight leading it reads confident without shouting. The system body keeps the page fast in Facebook's in-app browser on cellular.

### Hierarchy
- **Display** (400, clamp(44px, 12.4vw, 84px) on phones, clamp(52px, 7.2vw, 84px) from 760px, line-height 1.02, max 11ch): the hero H1 only, in white, with its last phrase in the accent.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08, -0.005em, balanced wrap): every section H2.
- **Row** (400, clamp(24px, 6.6vw, 30px), 1.1): service rows. The Facebook row is a smaller step at clamp(19px, 5.2vw, 22px) / 1.2.
- **Title** (400, 21px, 1.2; 22px from 1024px): step titles. The ready-panel H3 is 24px. The wordmark is 21px (24px from 760px).
- **Label** (400, 17px, 1.2): form labels and legends, in the display face.
- **Button** (400, 18px, 1): every pill button, in the display face. The header phone number uses the display face at 17px (20px from 760px).
- **Promise / Lede** (400, clamp(17px, 4.7vw, 20px) / 1.5 and clamp(17px, 4.6vw, 19px) / 1.7): the hero promise (max 30ch, 34ch from 760px) and section ledes (max 38ch). The closing line is clamp(18px, 5vw, 20px).
- **Body** (400, 16px, 1.7): running text, inputs, chips and the footer. Step text stops at 60ch.
- **Small** (15px): inline errors and the note under the form button. Field hints such as "(optional)" are 14px.
- **Eyebrow** (500, 14px, 1, 0.02em): eyebrow pills only.
- **Wordmark sub-line** (600, 11px, 0.08em, uppercase): "Construction LLC" under the wordmark, the only uppercase text.

### Named Rules
**The One Display Face Rule.** Every heading, row, label, button, step number and phone number is Cal Sans 400. Nothing is set bolder than 400 in the display face, and there is no second webfont.

**The Sixteen-Floor Rule.** Inputs, textareas and chips are 16px or larger so iOS never zooms on focus.

## Layout

The page is a single column of full-bleed bands inside a 1160px max wrap. The side gutter is 20px on phones and 40px from 760px. Bands are padded 64px on phones and 96px from 760px. The hero has no band padding; its copy column carries its own.

Band order: paper header, hero (navy under the photo), Services on paper, How it goes on deep slate, Our work on paper, the quote form on navy, Close on paper, footer on deep slate.

Breakpoints:
- **Below 380px:** chips tighten to 14px side padding.
- **760px:** wider gutter and band padding. The hero becomes two columns, copy beside the photo card. The work grid goes to four columns, and the Facebook row stops at 520px.
- **760px to 1099px:** the hero buttons stay stacked at full width, because the copy column is too narrow for two pills side by side.
- **1024px:** wider hero columns (1.15fr / 0.85fr, 56px gap). Services becomes a two-column split. The form band puts a sticky heading beside the card. Steps sit in three columns. The close band puts the heading and the button side by side.

Spacing rhythm: 12, 16, 20 and 28px gaps inside groups; 24 to 40px between steps; 28 to 36px from a heading to its list.

## Elevation & Depth

The system is flat. Depth comes from the alternation of the bands, from the 135° line texture on the dark bands and the hero, and from translucent ink tints. There are exactly two shadows. Neither is a hard offset shadow, and neither changes on hover.

### Shadow Vocabulary
- **Row lift** (`box-shadow: 0 8px 24px rgba(20,34,51,.07)`): the white Facebook row on paper, so it reads as a tappable slab.
- **Float lift** (`box-shadow: 0 10px 28px rgba(8,18,32,.3)`): the floating message circle, which sits over every band.

### Named Rules
**The Flat Bands Rule.** Cards, figures, form controls and buttons carry no shadow. A new surface separates itself by band or tint, not by lift.

## Shapes

The form language is soft and borderless:
- **Cards** (24px): the form card, the ready panel, work figures and the hero photo from 760px.
- **Facebook row** (20px).
- **Fields** (10px): inputs and textareas.
- **Pills** (999px): buttons, chips and eyebrows.
- **Circles** (50%): the arrow circles, step numbers, the eyebrow dot and the floating circle.
- **Focus outline** (6px): the radius of the global focus outline.

Strokes appear in only three places: the transparent 2px button and field border that changes colour on state, the 1px row divider, and the line button's 35% ink stroke. Photos always use `object-fit: cover` and are never stretched.

## Components

### Buttons
Every button is a confident, full pill.
- **Shape:** full pill (999px), at least 56px tall, 26px side padding, display face at 18px, optional 20px icon with a 10px gap.
- **Primary:** yellow fill and border with Slate Ink text. It is the hero message button, the close button and every form submit. Inside the form card and the ready panel it is full width.
- **Ghost:** transparent with On Dark text and a 70% On Dark 2px stroke. Hero only.
- **Line:** transparent with Slate Ink text and a 35% ink stroke. It is the ready panel's secondary action.
- **Hover (pointer devices only):** primary goes to Lit Yellow; ghost goes to a white stroke on a 10% white wash; line goes to a full ink stroke. Form buttons also gain a 2px Field Blue outline.
- **Press:** scale 0.98 over 0.12s.
- **Focus:** a 3px outline at a 3px offset (yellow on dark grounds); 2px Field Blue at a 2px offset inside the form.

### Eyebrow pills
A quiet label above the hero H1 and a few section headings, never on every heading. It is a 14px pill with a 7px yellow dot, a 6% ink fill on paper or a 12% white fill on dark, and 9px 14px padding. It is marked up as a `<p>`, has no hover state, arrow or shadow, and never uses a full yellow fill. This is Ellie's recorded exception in the calm band style; keep it to the hero and at most one or two section heads.

### Chips
- **Style:** Field Tint fill, 2px transparent border, 999px radius, at least 48px tall, 18px side padding, 16px system text.
- **State:** hover gives a Field Blue border. Selected is an ink fill with white text. Keyboard focus is a 3px Field Blue outline at a 3px offset, so focus stays visible on the ink fill.

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** Card White on the navy band.
- **Shadow Strategy:** none (see Flat Bands).
- **Border:** none.
- **Internal Padding:** clamp(20px, 5vw, 32px), with a 20px gap between fields, max 600px wide.
- **Ready panel:** replaces the form after submit and uses the same card. It holds a 24px H3, a 150px read-only textarea, a full-width primary "Open Messenger" button and a line "Copy message again" button.

### Inputs / Fields
- **Style:** Field Tint fill, 2px transparent border, 10px radius, 13px 14px padding, at least 52px tall (textareas 120px), 16px text, navy caret, Quiet Text placeholders.
- **Focus:** the border turns Field Blue, with no glow. Hover does the same on pointer devices.
- **Error:** a plain-sentence error in Error Red at 15px under the field, and an Error Red border. The error rule is more specific than the focus rule so the red border survives focus.

### Navigation
- **Header:** a paper bar, 64px tall (76px from 760px), with the top padding respecting the safe area. The wordmark is on the left: "True Custom" in the display face over an 11px uppercase "Construction LLC". The phone slot is on the right. Until the owner gives a number it reads "Phone coming soon" in 14px Quiet Text. Once CONFIG.PHONE is set it becomes a display-face tel link with a Yellow Ink phone icon. There is no menu.
- **Footer:** deep slate with the line texture, On Dark Soft text, and links in On Dark at least 44px tall that turn yellow on hover. The bottom padding (96px plus the safe area) clears the floating circle.

### Hero
On phones, their Cat 279D photo fills the navy band under a top-to-bottom ink overlay (86%, then 82% at 58%, then 40%). The copy sits over it: eyebrow, H1, promise and two buttons, stacked full width. From 760px the overlay is gone and the photo becomes a 24px 4:5 card (max 440px wide, max 600px tall) beside the copy on the textured navy band.

### Service rows
Each row is the whole link: the service name in the Row style, at least 76px tall, with a 1px divider between rows. A 44px arrow circle sits at the right end. On hover the arrow circle alone fills yellow; the row has no background, underline or shadow change. On focus the arrow fills yellow and takes a Field Blue outline. Tapping a row preselects the matching chip in the form.

### Numbered steps
An ordered list on deep slate. Each step has a 48px yellow circle with its number in the display face at 20px, a title in On Dark, and a sentence in On Dark Soft. It is one column on phones and three from 1024px.

### Work grid
4:5 figures with a 24px radius on a Photo Ground fill, with no captions and no overlays. On phones the grid has two columns and a full-width lead image. From 760px it has four columns, and the lead spans two by two. Images cannot be dragged or selected.

### Facebook row
A white 20px slab, at least 76px tall, with the row shadow. It holds a 30px Facebook-blue glyph, a display-face line, and the same arrow circle as the service rows, which again is the only thing that reacts to hover.

### Floating message circle
A 60px yellow circle fixed at the bottom right, inside the safe area, with a Messenger icon (a chat icon once a phone number is set). It slides up from 120px below over 0.35s cubic-bezier(.2,.8,.2,1) once the hero has left the screen. It hides again while the form or the closing button is in view. When hidden it is out of the tab order and aria-hidden. It is one circle, never a bottom bar.

### Motion
- **H1 bounce-in:** the hero H1 only. JS splits it into letters, keeping nested accent spans and wrapping each word in a nowrap span. Each letter moves from 50px right at opacity 0 to rest over 1s cubic-bezier(.34,1.56,.64,1), 20ms apart. The split waits for Cal Sans to load (capped at 800ms). An early `.hold` class hides the H1 until the split, so the heading never flashes plain; a 1.6s timeout releases `.hold` regardless. When the last letter lands, the original HTML is restored.
- **Fade-up:** only `.rise` elements that start below the first screen get `.below`. They rise 12px and fade in over 0.4s ease-out as they enter. Everything is visible at rest and without JS.
- **Reduced motion:** no split, no hold, no rise, no float or button transitions, and no smooth scroll. The plain heading shows at once.

## Do's and Don'ts

### Do:
- **Do** keep the band rhythm: paper, then navy or deep slate, then paper. The deep bands and the hero carry the 135° line texture at 3.5% white.
- **Do** put text on yellow in Slate Ink, and switch yellow-as-text on light grounds to Yellow Ink.
- **Do** set every heading, row, label and button in Cal Sans 400, and body text in the system stack at 16/1.7.
- **Do** use the radii: 24px cards, 20px Facebook row, 10px fields, 999px pills, 50% circles.
- **Do** give form controls Field Tint on the white card and a Field Blue border on hover and focus.
- **Do** let only the arrow circle react on link rows.
- **Do** gate hover styles behind `(hover:hover)` so taps never leave them stuck on.
- **Do** keep tap targets at least 44px (buttons 56px, chips 48px, fields 52px).

### Don't:
- **Don't** use yellow as text on paper or white, or white text on yellow.
- **Don't** go to a black ground; Deep Slate is the floor.
- **Don't** add shadows to cards, figures, fields or buttons. The Facebook row and the floating circle are the only lifted things.
- **Don't** add a second webfont or set Cal Sans above 400.
- **Don't** animate any heading other than the hero H1. Don't hide content at rest; only below-the-fold elements wait for the fade-up.
- **Don't** stretch a photo or blow the tall hero frame across a wide band; from 760px it is a card beside the copy.
- **Don't** add a bottom contact bar; the floating message circle is the only fixed control.
- **Don't** put eyebrows on every heading, give them hover or arrows, or fill them with full yellow.
