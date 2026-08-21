# Ruturaj & Tanvi — Wedding Site

Single-page wedding site. 13–14 December 2026, Balaji Sarovar Premiere, Solapur.

Everything lives in `index.html`. No build step, no dependencies. Edit the file, commit, done.

## Live URL

https://USERNAME.github.io/REPO-NAME

Replace `USERNAME` and `REPO-NAME` once Pages is switched on.

## How to update

Edit `index.html` directly on github.com: click the file, click the pencil icon, make the change, click **Commit changes**. The live site refreshes in about a minute. This works from a phone browser too.

## Still to fill in

**Phone numbers and emails.** Search the file for `add Ruturaj's number` and `add Tanvi's number`. Update the links:

```html
<a class="btn" href="tel:+911234567890">Call</a>
<a class="btn" href="mailto:name@example.com">Email</a>
```

Then delete the `<p class="fillnote">` line above each one.

**Theme and dress code.** Find the card titled `Theme &amp; dress code` in the "Good to know" section and replace the placeholder text.

**Venue photo.** The `<img>` in the venue section points at a Google-hosted URL that may expire. Upload your own photo to the repo and change the `src` to `venue.jpg`. Update the credit label in the corner to match.

## Notes

- The countdown targets `2026-12-14T12:21:00+05:30` — the Akshata Muhurt. It ticks in each visitor's local time and flips to a married message once it passes.
- Times in the itinerary are marked tentative. When they firm up, edit the `ev-time` values and remove the "tentative for now" eyebrow above the itinerary.
- Marathi text uses the Tiro Devanagari Marathi webfont, loaded from Google Fonts.
