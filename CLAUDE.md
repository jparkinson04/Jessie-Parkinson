# jessieparkinson.com

Personal hub site for Jessie Parkinson. One static page that routes visitors (mostly from LinkedIn) to the right project: Echo, Expert Voice, Seam Digital Studio, The Grad Groundwork.

## Rules
- Single file: everything lives in `index.html` (HTML, CSS, no JS needed). Do not add a framework, build step, or extra pages unless asked.
- Keep the look: black and white only. Centred black header with a slow-drifting black/grey/white gradient (CSS only, static under prefers-reduced-motion), a 160px circular photo with a thin white ring, white page, white project cards with a 2px black outline, square corners, no shadows, black buttons that invert to white on hover. Fonts are Space Grotesk (headings) and Inter (body) from Google Fonts. Nothing serif or cursive.
- Cards stay minimal: project name, one sentence, one button. No status labels, tags, icons, or numbered markers.
- Copy is plain and conversational, written for a stranger. Sentence case. No corporate or "LinkedIn" tone.
- Mobile first: check at 375px wide. Cards stack to one column under 680px.
- Keep the dark-mode colour tokens working when changing colours.

## Palette
- Black: #000000 (header, footer, buttons, card outlines, text)
- White: #FFFFFF (page, cards, button text, footer link outlines, photo ring)
- Dark grey: #3A3A3A (middle stop of the header gradient only)
- Light grey: #C8C8C8 (header description, footer small print)
- Card body text: #444444
- Dark mode inverts the page to black with white text; cards stay white with black text.
- No coral, plum or sunset gradient anywhere.

## Still to fill in (search `TODO` in index.html)
- Echo: link (no public URL yet)

## Adding a project
Copy one `<a class="card">` block inside `.grid`, change the name, sentence, button text and href.
