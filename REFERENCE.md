# CSS Idea Menu

Techniques for pushing `index.html` further toward "thing you'd mistake for a real newspaper at a glance." Done items are struck through; the rest are still up for grabs, no need to do all of it.

## Layout / structure
- Multi-column article text: `column-count` or `column-width` on story bodies — moot for now, stories are headline-only
- 3–5 column page layout instead of stacked sections
- Lots of small stories instead of a few big ones
- Asymmetrical alignment — photos/headlines that don't line up neatly
- ~~"Continued on Page A7" style fake continuations~~ — done (`.continued`, used on a few stories instead of body copy)

## Typography
- ~~Serif body/headline font pairing~~ — done (Playfair Display + PT Serif)
- ~~Headline size hierarchy~~ — done (`.story--lead` vs. regular)
- ~~Tiny uppercase section labels~~ — done (`h2`)
- ~~Bylines~~ — done (`.byline`)
- Drop cap — tried, then removed once stories went headline-only (nothing for it to act on)

## Visual texture
- ~~Off-white paper background~~ — done (`--paper: #f4efe0`)
- ~~Subtle background texture~~ — done (repeating-linear-gradient grain)
- ~~Rule lines between sections~~ — done (`.story`, `.box--corrections`)
- ~~Photo borders that look pasted-on rather than stretched~~ — done (`.story-photo img`, used for Jack and Paul Sr.)
- Uneven photo sizes instead of a uniform grid
- Occasional slight photo rotation (`transform: rotate(-1.4deg)`)

## Components
- ~~Pull quotes~~ — done (`.box--pullquote`, used for Opinion)
- ~~Captions: small, gray~~ — done (`.story-photo figcaption`)
- Floating sidebar boxes ("Did You Know") — could reuse the `.box` pattern already used for Market Watch/Prediction Market
- ~~Fake ads~~ — done (`.box--ad`, used for Classifieds)
