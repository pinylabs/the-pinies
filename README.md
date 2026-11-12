# The Pinies' studio

> **Preview: the full template is being built by the Pinies.** This repository is a small working EmDash site: its home page is the accepted design, and the rest is EmDash's own `portfolio-cloudflare` template. The Pinies' real build lands here later.

An illustrated EmDash portfolio: a studio's team, its work as ticket stubs, and each piece's record.

## Start it

- **In Piny:** pick it in the Templates tab.
- **Outside Piny:** `npm create astro -- --template github:pinylabs/the-pinies`, then `pnpm install` and `pnpm dev`, and open `/_emdash/admin` to set up the site.

It needs Node 22 or later and pnpm. On Cloudflare it uses a D1 database (`DB`) and an R2 bucket (`MEDIA`), as EmDash's Cloudflare templates do.

## Its look

Astro with Tailwind CSS 4. Every colour, face, size, corner and width is a token in `src/styles/theme.css`, the one file to edit to retheme the site; `src/styles/global.css` holds the dark variant, which follows the footer's theme switcher and otherwise the system, and the few shared patterns. Motion is mild and stops under reduced motion.

## Photos and video

They are linked from their sources and never copied into this repository:

- No photos: an illustration drawn in the page, and the Pinies' faces.
- The work's pictures are each site's own preview, from its repository: [Saltwater](https://github.com/pinylabs/saltwater) and [Brew Guide](https://github.com/pinylabs/brew-guide).

## Licence

MIT. Built on EmDash's `portfolio-cloudflare` template, MIT, Copyright 2026 Cloudflare Inc.; its notice is kept in [LICENSE](LICENSE). Made by the Pinies in [Piny](https://piny.studio/home/). The Piny Studio mark in `public/brand` is Piny's and is not covered by this template's MIT licence.
