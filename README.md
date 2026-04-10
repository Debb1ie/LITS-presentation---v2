# She's the IT: Women in Tech
### A Presentation by Precious Manucom, President of DEVCON Manila
Delivered at the Letran Information Technology Society (LITS) Webinar — April 10, 2026!

---

## Overview

This is a self-contained, single-file HTML presentation deck built for the LITS webinar "She's the IT: Women in Tech." It covers the state of women in the Philippine technology industry, the retention crisis, community-building, and actionable steps for students.

The file requires no build tools, no frameworks, and no internet connection after initial load. Open it in any modern browser and it runs.

---

## File Structure

The entire presentation lives in one file: `index.html`

It includes all CSS, JavaScript, font imports (via Google Fonts CDN), and slide content inline. There are no external dependencies to manage and no separate asset folders required beyond the photos you add.

---

## Slide Inventory

| # | Type | Title / Purpose |
|---|------|-----------------|
| 1 | Title | She's the IT — opening title card |
| 2 | Opener | Hook question: "Was she a woman?" |
| 3 | Story | About the speaker — Precious Manucom |
| 4 | Gallery | DEVCON Manila — who we are |
| 5 | Timeline | Today's agenda |
| 6 | Stat | 27% — women in the Philippine tech workforce |
| 7 | Two-column | The retention crisis — entry vs. senior levels |
| 8 | Opener | Part 2 transition — "The Six Walls" |
| 9 | Grid | The six walls women hit in tech |
| 10 | Quote | Luvvie Ajayi Jones |
| 11 | Story | Psychological safety as a foundation |
| 12 | Compare | School vs. industry |
| 13 | CTA | "Refuse to shrink" |
| 14 | Gallery | DEVCON community photos |
| 15 | Timeline | Building your support system |
| 16 | Grid | Six actions you can take this week |
| 17 | Quote | Michelle Obama |
| 18 | CTA | Inclusion is not a metric |
| 19 | Certs | Certifications and recognitions (photo slots) |
| 20 | Gallery | DEVCON Manila event highlights |
| 21 | Gallery | For LITS students — next steps at Letran |
| 22 | CTA | "The next generation of girls" |
| 23 | Two-column | What companies must do — retention fix |
| 24 | Certs | Awards and milestones (photo slots) |
| 25 | CTA | "You are already the IT" |
| 26 | Opener | Q&A open floor |
| 27 | Story | Stay connected — join DEVCON Manila |
| 28 | Thank You | Closing card |

---

## Adding Your Photos

Every photo placeholder in the deck is a dashed box labeled with what goes there and a small tip: `replace with <img src="...">`.

To replace a placeholder, locate the corresponding `photo-slot` div in the HTML and swap it with a standard `<img>` tag:

```html
<!-- Before -->
<div class="photo-slot" style="border-radius:12px">
  ...placeholder content...
</div>

<!-- After -->
<img src="your-photo.jpg"
     style="width:100%;height:100%;object-fit:cover;border-radius:12px;display:block">
```

Photos should be placed in the same folder as `index.html` or referenced by a relative path. For best results use images at least 800px wide. JPG and WebP both work well.

### Photo placement guide

| Slide | Photo description |
|-------|------------------|
| 1, 28 | Headshot or powerful speaking photo of Precious Manucom |
| 3 | Speaker headshot or onstage moment |
| 4 | DEVCON Manila event and team photos (two slots) |
| 6 | Event or audience photo, or infographic |
| 7, 23 | Women in workplace, panel, or conference setting |
| 10, 17 | DEVCON event or women in tech community |
| 11 | Team, workshop, or collaborative setting |
| 13, 18, 22, 25 | Speaker onstage or leadership moment |
| 14, 20 | DEVCON Manila event gallery (five slots each) |
| 19, 24 | Certificate or award images (six slots each) |
| 21 | LITS event and officer photos (two slots) |
| 27 | DEVCON community group photo |

---

## Navigation

| Action | Result |
|--------|--------|
| Arrow Right / Arrow Down / Space | Next slide |
| Arrow Left / Arrow Up | Previous slide |
| Home | First slide |
| End | Last slide |
| F | Toggle fullscreen |
| Click left or right edge of screen | Previous / next slide |
| Swipe left or right (touch) | Next / previous slide |
| Click a dot in the bottom bar | Jump to that slide |
| Type a number in the bottom-left input, press Enter | Jump to that slide number |

The progress bar at the top of the screen tracks position through the deck.

---

## Theme

The presentation ships in dark mode. Click the toggle in the top-right corner to switch between dark and light. The theme choice is not persisted between sessions — it resets to dark on reload.

---

## Customization

### Speaker details
The speaker name, role, organization, and contact email appear in three places: the title slide (slide 1), the thank you slide (slide 28), and the top bar. Search the file for `Precious Manucom` and `pmanucom@devcon.ph` to update them.

### Event details
The event name and date appear in the top bar and the title slide. Search for `April 10, 2026` and `LITS Webinar` to update them.

### Slide content
All slide content is defined in the `slides` array near the bottom of the `<script>` block. Each slide is a plain JavaScript object. Text, tags, bullet points, and timeline items can all be edited there without touching the rendering code.

### Colors
The color system uses CSS custom properties defined in `:root[data-theme="dark"]` and `:root[data-theme="light"]`. The primary accent is `--rose`, the secondary is `--gold`, the tertiary is `--teal`, and the fourth is `--lilac`. Changing these values will update the entire deck.

---

## Browser Support

Tested in Chrome, Firefox, Safari, and Edge (all current versions). The presentation uses CSS custom properties, flexbox, grid, and the Fullscreen API — all widely supported. Internet Explorer is not supported.

The font stack (Cormorant Garamond, Syne, JetBrains Mono) loads from Google Fonts on first open. If presenting offline, either download the fonts locally or the deck will fall back to system serif and monospace fonts.

---

## Printing / Export

The deck is not optimized for print. For a PDF export, open the file in Chrome, enter fullscreen, and use the browser's print-to-PDF function set to the slide aspect ratio. For a proper export use a screen capture tool or a browser extension designed for HTML-to-PDF conversion.

---

## License

Presentation content and design copyright Precious Manucom / DEVCON Manila, 2026. The underlying template code may be reused freely for non-commercial presentations with attribution.
