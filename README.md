# Stone Harbor Chronicle

A joke newspaper mockup for a family beach vacation in Stone Harbor, NJ. Satirical "front page" headlines about family members (Jack's pickleball collapse, Matthew walking on water, Melissa's gambling habit, Paul Sr.'s pool betrayal), plus classic newspaper filler: weather, classifieds, corrections, stats.

Stories are headline-only by design — no body copy. Some just end after the byline; a few carry a fake "» Continued on Page B6" jump line for flavor.

## Files

- `index.html` — the page. Two-column layout (main stories / sidebar), driven entirely by `style.css`.
- `style.css` — all styling.
- `images/jack-print.jpg`, `images/paul-sr-print.jpg`, `images/matthew-print.jpg` — cropped/processed, web-sized photos used in the Front Page, Lifestyle, and Local News stories. The `-print` files are the ones referenced from HTML; the unsuffixed originals (`jack.jpeg`, `paul-sr.jpeg`, `matthew-surf.jpeg`) are the untouched source photos, kept for re-cropping later.
- `images/placeholder.svg` — unused.

## Preview

Just open `index.html` in a browser — no build step, no server required.

## Feature toggles

A couple of sidebar widgets are still being decided on and can be switched off with a one-line edit — see the `FEATURES` object in the `<script>` near the end of `index.html`. Currently: `music`, `marketWatch`, `predictionMarket`. Set any to `false` and reload to hide it.

## Status

Real newspaper look is in: Playfair Display/PT Serif pairing, headline hierarchy, rule lines instead of boxes-around-everything, a pull-quote, a fake-ad treatment, and two real photos with pasted-on borders and captions. Sections cover Front Page, Local News, Business, Lifestyle, Food, Music, Sports Stats (scoreboard style), Opinion, Market Watch, Prediction Market (styled like a real one — percentage callout, probability bar, colored YES/NO), Classifieds, Corrections, and Vacation by the Numbers. Horoscope, Police Blotter, and Weather were tried and cut. See `REFERENCE.md` for remaining unused ideas.
