# True Custom Construction LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/trueCustomConstruction/ · **Repo:** https://github.com/10elizabethbell/trueCustomConstruction · **Built:** 2026-10-18 from Muse brief 2026-10-18 (Essex County Contractor Referrals group post)

## What's built
- One page, phone first: header (wordmark + phone slot), hero, What we do / How it goes, Our work, Free quote form, close, footer.
- **World:** a soil cutaway under an overcast sky. Topsoil over clay and stones, a dark board-and-batten wall (taken from their Facebook profile-photo house) with a downspout, rain, puddles, turf. Sod strips (grass on a soil band) are the section edges. The grass sways and leans away from the pointer or finger.
- **Signature element:** you drive their yellow tracked Cat 279D skid steer across a lumpy yard that slopes *toward* the house. The bucket grades it to a slope that falls away from the house. Rain and downspout water stop pooling against the foundation and run off, and sod grows in on finished grade. It drives itself until touched. Drag works in every direction on phones (`touch-action:none` on the yard, pull-to-refresh off). On desktop (≥1024px) the scene is mirrored so the house and window fill the right side of the hero, and rain never falls across the text. When the whole lawn is finished it waits 13s and fades into a fresh yard. Constants sit at the top of the hero IIFE (`T = {...}`).
- **Contact:** the primary button opens Facebook Messenger (`m.me/61585918380470`). The quote form builds the message, copies it, and offers "Open Messenger" with the message shown in a box in case the copy is blocked (Facebook's in-app browser).
- **One switch for the phone number:** set `BIZ.PHONE` at the top of the script. The header's "Phone coming soon" becomes a tap-to-call number, the footer gets the number, and the form hands off as a pre-filled text (`sms:`) instead of Messenger. Tested both paths headlessly.
- Photos: 4 stills cropped from their job-site video (`img/work-01..04.webp`) plus their profile photo (`work-05.webp`), 720px WebP, lazy-loaded. 5 photos, ~400KB in total.

## Assumptions I made
- **Voice "we":** the post reads like a crew, and the video shows a skid steer plus a dump truck.
- **Copy is mine, not theirs:** the headline "Built right from the dirt up.", the promise line and the three steps. It only claims what the post says (remodels, sod prep, grading for drainage, free consultation) and what the video shows (skid steer, dump truck).
- **Equipment:** the skid steer has a "Western States" Cat dealer decal, so it may be rented. The copy says "we show up with", never "our own".
- **The profile-photo house is their build.** It's a new dark board-and-batten house in snow. I used it as a work photo and as the hero wall. Confirm or swap.
- **Colors:** there's no logo. Construction yellow for the action comes from the Cat machine in their video, charcoal-blue from the house siding, cedar from its garage door, on a cool concrete ground.
- **Messenger link:** `m.me/<page id>` should open their page's Messenger. The `?text=` prefill is a best effort; Messenger often ignores it, so the copy-and-paste step is the real path.

## Placeholders and gaps
- **Phone: none published.** The header and footer show "Phone coming soon" (see `BIZ.PHONE`).
- **Email: none.** There's no footer email line; add one when known (footer only).
- **Service area:** unknown, so there's no area section. The video's dry hills and the Western States Cat dealer decal suggest the inland Northwest, but I didn't use that.
- No logo: the wordmark is set in the site's lettering, and the favicon and home-screen icon are a "TC" monogram (`apple-touch-icon.png`).
- No reviews, prices, hours, owner name, license or insurance, so none appear on the page.
- No remodel photos at all, though remodels are listed first in their post.

## Questions for the owner
- Phone number, and does it take texts? Email?
- Which towns do you cover?
- Owner's first name (for "Message Tom" style buttons and a personal line)?
- Remodel photos, and before/after pairs of a graded yard → sod?
- Is the dark board-and-batten house yours? Are the skid steer and dump truck yours?
- Licensed/insured? Years in business?

## Ideas not built (yours to pick)
- **Runner-up world:** sod rolls. A strip of sod unrolls across the hero under your finger, seams knitting together, with the section edges as rolled sod. Other worlds I considered: topographic contour lines that flatten under touch, skid-steer track prints laid by the pointer, a string line and grade stakes, and a remodel framing/blueprint world.
- A before/after slider once they send a "before" of a yard.
- Show the dump truck in the hero (dropping a load of topsoil on the first touch). Their video frames of it were too blurry to use as a photo.
- A short muted clip from the video (skid steer working, ~6s) in the gallery. Skipped for weight and because it's handheld.
- Use the hero's finished lawn as a "done" moment: a small "Graded. Water runs away from the house." note.
- An area line in the footer once the towns are known (plain text, never pills).

## Not verified
- Real-device touch (iOS Safari and Facebook's in-app browser), frame rate on older phones.
- That `m.me/61585918380470` opens the right Messenger thread in the app.
- Whether clipboard copy works inside Facebook's in-app browser (there's a visible fallback either way).
- The SMS hand-off on a real iPhone/Android (only tested headlessly with a dummy number).
