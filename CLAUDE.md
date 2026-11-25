# DevStach

A developer knowledge hub for snippets, commands, prompts, notes, files, images, links and custom types.

## Context Files

Read the following to get the full context of the project: 

- @context/project-overview.md
- @context/coding-standards.md
- @context/ai-interaction.md
- @context/current-feature.md


## Commands

- `npm run dev` — start dev server (Turbopack)
- `npm run build` — production build
- `npm run lint` — ESLint (Next.js config)
- `npm run start` — run production server

## Architecture

Fresh Next.js 16 App Router project with Tailwind CSS 4. Source lives in `src/app/`. Currently only has `layout.tsx`, `page.tsx`, and `globals.css` — no routes, components, or utility files yet. Next.js config is in `next.config.ts`; no custom webpack or experimental flags at this time.

## Notes

- `globals.css` is intentionally stripped of boilerplate styles.
- The `AGENTS.md` file in the project root contains an auto-generated warning from `next dev`; do not commit changes to that block.
- When adding new pages, follow the App Router convention: create a `page.tsx` inside the route folder.
