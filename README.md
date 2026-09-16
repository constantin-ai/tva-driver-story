# TVA Driver Story

Full-screen, Instagram-Story-style page for **re-engaging cold/old CDL leads**.
Vertical video + burned-in captions + tap-to-advance + one tappable CTA.

Sent as a link via SMS (the REACTIVARE reactivation flow). Custom domain: `drive.tvalogistics.com`.

Story arc: hook ("still looking for the right seat?") → what's changed → W-2 pay →
newer trucks / miles → home time & 1-day orientation → "still interested? let's talk."

## Swap before/when going live
- `truck.mp4` — replace with the real UGC creator clip (vertical 9:16). Keep it light (< ~3 MB) so it loads fast over cell data.
- `poster.jpg` — first frame shown instantly while the video loads.
- CTA `href` in `index.html` (search "CHANGE THIS") — point to the pre-qualify / recruiter link you want returning leads to hit.
- Captions array in `index.html` — edit the `caps` list; progress bars auto-match the number of captions.
