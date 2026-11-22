# VEXAMIA — Brand Hub Site

A plain HTML/CSS static site for the VEXAMIA brand. No build step, no JavaScript, no forms, no store, no checkout.

**Tagline:** Enter the Unexpected.
**Contact:** mrleosura@gmail.com

## Files

| File | Purpose |
|---|---|
| `index.html` | The single page: hero, brand story, channel links, sponsors & press contact |
| `style.css` | Mobile-first responsive styles (Midnight background, sunset gradient accents) |
| `favicon.jpg` | Site icon (the VEXAMIA sunset symbol) |
| `assets/logo.jpg` | Hero logo image (sunset symbol) |
| `assets/og-image.jpg` | Social-preview image (Open Graph / Twitter card) |

## Official channels linked from the page

- YouTube — https://www.youtube.com/@VEXAMIA
- TikTok — https://www.tiktok.com/@gta6.leovicecity (username change to @vexamia pending)
- Instagram — https://www.instagram.com/vexamiaworld/

## Publishing to GitHub Pages

1. Create a GitHub repository (for example `vexamia.github.io` for a user site, or any repo name for a project site).
2. Copy the contents of this `site/` folder into the repository root and push.
3. In the repository: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, pick the default branch and `/ (root)`, and save.
4. The site goes live at `https://<username>.github.io/` (or `https://<username>.github.io/<repo>/` for a project site).

Nothing in this folder is published yet — publishing requires the project owner's approval.

## Notes

- Fonts (Space Grotesk, Inter) are referenced by name with system fallbacks; the site does not bundle webfont files, so it renders in a close geometric/grotesque fallback where the fonts are not installed. Both fonts are SIL OFL 1.1 if they are ever self-hosted.
- Colors and usage rules: see `../BRAND_KIT.md`.
