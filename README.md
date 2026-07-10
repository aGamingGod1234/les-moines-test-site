# Les Moines Premium Bakery Test Site

Project label: `les-moines-test-site`

Les Moines is a fictional premium French bakery concept built as an image-led interactive website. It uses a cool cobalt and porcelain identity, an expandable pastry counter, a three-stage craft dial, an atelier story, a local morning-box builder and practical demo details.

## Stack

- React 19
- TanStack Start with file routes under `app/src/routes`
- Vite 7 and Bun
- Tailwind v4 CSS tokens
- Framer Motion for scroll and state motion
- Self-hosted Bodoni Moda and Manrope variable fonts

## Project capsule

- Type: standalone website
- Status: fictional test site, not a real client or bakery
- Primary action: compose a local pastry-box demo
- Motion level: premium and restrained, with reduced-motion support
- Deployment target: public Vercel preview first

## Local commands

Run from `app/`:

```bash
bun install
bun run qa:fill -- --strict
bun run typecheck
bun run build
bun run build:design
bun run dev
```

## Source truth

- `app/design-brief.md` contains the locked system and section ledger.
- `refs/README.md` documents the seven generated visual-contract boards.
- `app/public/assets/` stores the inspected production imagery and monogram.
