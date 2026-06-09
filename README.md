# VYV House

VYV House is the Next.js site for VYV House, a residency described on the site as “a house for builders with taste.” The repo holds the landing page, resident and guestbook data, shared styles, and metadata that shape the current site.

## Tech stack

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS v4
- `lucide-react`

## Local development

Basic local development:

```bash
npm install
npm run dev
```

Checks before opening a PR:

```bash
npm run lint
npm run build
```

Run the production build locally:

```bash
npm run start
```

## Repository map

- `src/app/page.tsx` - main landing page and inline content arrays
- `src/app/globals.css` - global styles, CSS tokens, and reusable classes
- `src/app/layout.tsx` - metadata, fonts, and document-level setup
- `src/data/residents.ts` - current resident data
- `src/data/guestbook.ts` - guestbook entries
- `AGENTS.md` - coding-agent guidance for this repository
- `docs/brand/README.md` - lightweight brand guide for current site conventions

## Where to edit content

- Update the page copy and section structure in `src/app/page.tsx`
- Update resident profiles in `src/data/residents.ts`
- Update guestbook entries in `src/data/guestbook.ts`
- Update site metadata, fonts, and social preview details in `src/app/layout.tsx`

## Design and copy guidance

- Preserve the existing logo and visual identity.
- Treat the current site language as the source of truth.
- `house protocol` is already an existing site concept.
- Reuse existing CSS tokens and classes in `src/app/globals.css` before adding new ones.
- Keep copy short, specific, and close to the existing VYV tone.
- Avoid generic startup, coworking, accelerator, or corporate language.
- Be careful with numeric claims like resident counts because the content data can change.

## Notes for future contributors

- This repo is intentionally content-led. Most visible changes should start in the data files or the landing page copy.
- If you need to add a new pattern, check whether an existing token or reusable class already covers it.
- Follow the repo guidance in `AGENTS.md` before making code changes.
- Keep edits small and easy to review.
