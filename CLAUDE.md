# jessieparkinson.com

Personal hub site for Jessie Parkinson. One static page that routes visitors (mostly from LinkedIn) to the right project: Echo, Expert Voice, Seam Digital Studio, The Grad Groundwork.

## Rules
- Single file: everything lives in `index.html` (HTML, CSS, no JS needed). Do not add a framework, build step, or extra pages unless asked.
- Keep the look: black and white only. Centred black header with a slow-drifting black/grey/white gradient (CSS only, static under prefers-reduced-motion), a 160px circular photo with a thin white ring, white page, white project cards with a 2px black outline, 20px rounded corners, no shadows, a 16:9 preview screenshot across the top of each card, black buttons that invert to white on hover. Fonts are Space Grotesk (headings) and Inter (body) from Google Fonts. Nothing serif or cursive.
- Cards stay minimal: preview screenshot, project name, one sentence, one button, and a row of social icons (inline SVG symbols at the top of `<body>`: LinkedIn, Instagram, TikTok). No status labels, tags, or numbered markers.
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

## Still to fill in
- Nothing outstanding. Echo currently points at its Vercel address (echo-kappa-teal.vercel.app); swap in a custom domain when there is one.

## Adding a project
Copy one `<li class="card">` block inside `.grid`, change the name, sentence, button text, hrefs and social links. Add a 1200x675 JPEG screenshot to `assets/` (the app previews are real screenshots cropped to 16:9) and point the `<img class="preview">` at it.
