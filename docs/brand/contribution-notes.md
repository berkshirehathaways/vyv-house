# Contribution notes

Use these notes when making safe updates to the current site.

## Resident entries

- Update residents in `src/data/residents.ts`.
- Keep names, links, roles, and descriptions short and specific.
- Keep the current resident data structure intact.

## Guestbook entries

- Update guestbook entries in `src/data/guestbook.ts`.
- Keep notes concise and personal.
- Preserve the existing `Guest / Builder` framing and trace language where it already fits.

## Page copy

- Update landing page copy in `src/app/page.tsx`.
- Reuse the current section structure and copy patterns when possible.
- Keep copy close to the existing VYV tone.

## Metadata and social previews

- Update metadata, fonts, and social preview settings in `src/app/layout.tsx`.
- Keep titles and descriptions aligned with the current site language.

## Numeric claims

- Be careful with counts and totals, including resident counts.
- Treat these as content data, not fixed identity claims.
- If the number changes, update the underlying data and the page together.

## New visual patterns

- Add new visual patterns only when an existing token or class does not already cover the need.
- Keep any new pattern thin, restrained, and consistent with the current page.
- Do not add a new design system on top of the existing one.

## Before code changes

- Read `AGENTS.md` first.
- Follow the repository guidance there before editing source files.
