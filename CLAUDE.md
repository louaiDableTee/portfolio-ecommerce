# CLAUDE.md — e-commerce portfolio

This repository is **Louai Bouraoui's e-commerce portfolio** (live: https://louai-bouraoui-ecommerce.vercel.app, Vercel project `portfolio-ecommerce`).

**`portfolio2` is a different project**: the separate SEO / marketing portfolio (https://louai-bouraoui-marketing.vercel.app). It is never edited from here. Reading it is fine (for example to copy an image); changing it, or pushing to it, is not.

## Rules

- **FR and EN always in sync.** Every change is made in `content/fr.json` and `content/en.json` (and the template if the structure changes). French is the main language at `/`, English lives under `/en/`.
- **No location and no availability anywhere:** no city, country of residence or "open to work in…" wording, in text, meta tags, structured data or images. "Tunisie" is allowed only where it describes the store's market (TND prices, delivery, autocomplete) and in the school's name.
- **No CV download.** No CV link, button or PDF. The contact areas say "CV envoyé sur demande." / "CV available on request."
- **Never invent facts or numbers.** Only cut, move or reformat what is already on the site, or use what Louai has confirmed in the conversation.
- **Espace Deals is always called a "boutique de démonstration"** (demo store). It runs locally; screenshot labels say `espacedeals.local`, never `espacedeals.com`. No claims of real customers, sales or results.
- **AI tools are named only: Claude Code, Claude Design, Cowork.**

## Workflow

- Work on branches. Vercel builds a preview for each branch.
- **Never merge to `main` without Louai's explicit OK.** Pushing to `main` deploys the live site.
- Run `npm run check` before pushing (it builds and checks links, headings, alt text, FR/EN parity, hreflang).
- Check pages at 390 px and 1280 px, in FR and EN, with no horizontal scroll.
- Keep `main.ts` and `styles.css` plain: Vite + TypeScript + hand-written CSS, no new framework.
