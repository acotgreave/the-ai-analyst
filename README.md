# The AI Analyst? — home page

Static site for **https://aianalyst.howtospeakdata.com**, served by GitHub Pages from the `main` branch root. No build step.

## Adding a new episode

1. In `index.html`, copy the "Latest episode" block's details into a new `<li class="card">` at the **top** of the "All episodes" list.
2. Update the "Latest episode" block with the new video ID, title, date, guest and description.
3. Update the "N episodes so far" count in the hero.
4. Commit and push. Pages redeploys in about a minute.

Thumbnails come straight from YouTube: `https://i.ytimg.com/vi/<VIDEO_ID>/maxresdefault.jpg`.

## Files

- `CNAME` — the custom domain for GitHub Pages. Don't delete it.
- `og-image.png` — the social share card (1200×630).
- `htsd-mark.svg`, `favicon.svg` — How To Speak Data mark.
