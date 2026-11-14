# Yara of Kijani — GitHub Pages site

Public website for **Yara of Kijani**, Book 1: *Daughter of Two Worlds*,
written by BiomassFlood, with AI assistance from Luna for drafting and editing.

This is a plain static site — one `index.html` plus files under `assets/`.
No build step, no server, no database. It works on GitHub Pages as-is.

## What's in here

- `index.html` — the whole site: book trailer, story overview, characters,
  Vey'kar species, Kijani, outline, disclaimer, and the prologue + Chapters 1–6
  in full text with audiobook players (6 of 20 chapters, 168 min 44 sec total).
- `assets/` — 19 files: 7 chapter MP3s (prologue 6:39, Ch1 24:18, Ch2 16:46,
  Ch3 23:02, Ch4 29:22, Ch5 32:42, Ch6 35:53), story-overview + 6 trailer
  narration clips, hero + 4 trailer images.
- `icon.webp` — site icon (not currently referenced by the page).
- `.nojekyll` — tells GitHub Pages to serve the files exactly as they are.

Features: click-to-listen read-along (tap any story paragraph and the audio
jumps to that part — 527 mapped paragraphs), native audio players, autoplay
toggle (off by default), pause-when-you-leave, and a Now Playing bar.

## How to deploy (GitHub Pages)

1. **Create a GitHub account** at https://github.com/signup (free),
   if you don't have one yet.
2. **Create a new repository** (the `+` menu → New repository):
   - Name: `the-yara-chronicles`
   - Public
   - Leave "Add a README file" **unchecked** (this folder already has one).
3. **Upload these files** to the repository:
   - On the new repo page, click **"uploading an existing file"**.
   - Drag in everything in this folder: `index.html`, `README.md`,
     `.nojekyll`, `icon.webp`, and the whole `assets` folder.
     (If your browser won't upload the `.nojekyll` file because it's hidden,
     create it on GitHub instead: Add file → Create new file → name it
     `.nojekyll` → leave it empty → Commit.)
   - Click **Commit changes**.
4. **Turn on Pages:** repo **Settings → Pages** (left sidebar) →
   under "Build and deployment", Source: **Deploy from a branch**,
   Branch: **main**, Folder: **/(root)** → Save.
5. **Wait a minute or two.** GitHub will show your live address at the top
   of the Pages settings, like:
   `https://<your-username>.github.io/the-yara-chronicles/`
   Open it in Chrome on your phone — it's a normal website, no Muse app needed.

## Updating the site later

When a new chapter is written (Chapter 7 is next), replace `index.html` and
add the new chapter's MP3 to `assets/` in the repo (same upload flow), and
the live site updates automatically. The URL stays the same — no new links.

## Notes

- The site previously lived on Muse-only links, which only opened inside the
  Muse app and whose audio seeking did not work on the user's phone. This
  GitHub Pages version is a real website that opens in any browser.
- Chapter 2's audio is missing its last two paragraphs (they were never
  recorded); the recap lines at the top of Chapters 2–6 are headers only and
  are intentionally not read aloud. Those two paragraphs are also unmapped
  for click-to-listen.
- All story text, characters, and worldbuilding are the author's original
  work. See the disclaimer section on the site.
