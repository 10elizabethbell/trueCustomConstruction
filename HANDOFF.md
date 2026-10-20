# True Custom Construction LLC — handoff at ~60% (calm revamp)

**Live:** https://10elizabethbell.github.io/trueCustomConstruction/ · **Repo:** https://github.com/10elizabethbell/trueCustomConstruction · **Built:** 2026-10-18, revamped 2026-10-19 under the calm band style · Muse brief 2026-10-18

## What changed in the revamp (2026-10-19)
- The drivable skid-steer soil-cutaway hero and the sod-strip section edges are gone. That build is in git history (`eb4f486`) and is the runner-up below.
- The page now uses the calm band style: paper, slate navy and deep slate bands, Cat yellow as a fill, Cal Sans headings, pill buttons, 24px cards, and eyebrow pills on the hero and "What we do".
- **Hero:** their own Cat 279D video frame (`img/hero.webp`) sits under a slate overlay on phones. The worst-pixel contrast is 6.3:1 or better for text. From 760px up, the tall 720x1280 frame sits beside the copy as a 24px card, because stretching it across a wide band would blow it up (calm-photo-style item 7).
- **Motion:** the H1 bounces in letter by letter. It waits for Cal Sans (800ms at most), is held hidden until it splits so it doesn't flash, and restores the plain H1 afterwards. Sections fade up. Reduced motion and no-JS show everything at once.
- **Floating message circle:** shows after the hero, and hides over the form and over the closing button.
- **Order:** hero → What we do (3 rows that pre-select the form chip) → How it goes (3 steps) → Our work (5 photos plus "Click to see more of our work." Facebook row) → form → close → footer.
- **Copy:** "Graded right. Built right." Every "free quote" became "free consultation", the brief's own wording. Repeated phrases are cut. The work-05 alt text no longer claims the house as their build.
- **Photos:** `work-01` was dropped because it duplicated the hero. `work-06` is a new graded-yard frame from the video.
- **New assets:** og image, a TC favicon and home-screen icon in the new palette, and a provenance sidecar for every raster.
- **Verified** in Chromium and WebKit at 360, 390, 430, 820 and 1440px:
  - no sideways scroll
  - H1 and primary button on the first phone screen
  - float states
  - form errors, including the error border on focus
  - Messenger hand-off text decodes correctly

## Contact wiring
- No phone is published. The header's top-right corner shows "Phone coming soon".
- Every button opens `m.me/61585918380470`. The form writes the message, copies it, and shows it with "Open Messenger" and "Copy message again".
- **One switch:** set `CONFIG.PHONE` at the top of the script. That turns on the header and footer number and makes every message button a pre-filled text (`sms:`).

## Assumptions I made
- "We" voice (a crew with a skid steer and a dump truck).
- The colours are mine; there's no logo. The yellow comes from the Cat in their video, the navies from the dark house in their profile photo.
- The headline and promise are my copy and claim only what the brief says.

## Placeholders and gaps
- **Phone, email, service area, owner name, hours, reviews, licence and insurance:** none published.
- **No place in the H1** (a house rule) because no area is known.
- No logo, so the wordmark and the TC icon use the site's lettering.
- No remodel photos.

## Questions for the owner
- What's your phone number, and does it take texts? Email?
- Which towns do you cover?
- Owner's first name?
- Remodel photos, and a before/after of a yard?
- Is the board-and-batten house (work-05) your build? If not, cut it.
- Are the skid steer and truck yours?
- Licensed and insured?

## Ideas not built (yours to pick)
- **Runner-up signature hero:** the drag-to-grade skid steer (git `eb4f486`). Other worlds: sod rolls that unroll, contour lines that flatten.
- **Conflicts kept by house rule:** Impeccable flags the eyebrow pills, the bounce-in with overshoot, the floating circle, the fade-up on every section and the band texture. All of them stay.
- Self-host Cal Sans to drop the Google Fonts chain (the sweep suggested it). The skill allows Google Fonts.
- Hide the form when JS is off.

## Docs
- `DESIGN.md` and `.impeccable/design.json` were regenerated from the calm build (2026-10-20); the detector shows no design-system findings. Its two remaining findings (hero padding, band texture) are waived in `.impeccable/config.json`.

## Not verified
- Whether `m.me/61585918380470` opens a chat on a real phone. On 2026-10-20 it redirected (302) to `m.facebook.com/msg/…`, which is the good sign (a dead profile ID gives a 200 with no redirect), but nobody has tapped it yet.
- Clipboard copy and the hand-off inside Facebook's in-app browser.
- Real-device iOS and Android.
