# Saurabh Jain — React Portfolio

A responsive, single-page React + Vite portfolio inspired by a modern LinkedIn/engineering portfolio aesthetic.

## Run locally

Requirements: Node.js 18+.

```bash
npm install
npm run dev
```

Then open the local URL printed by Vite.

## Production build

```bash
npm run build
npm run preview
```

## Customize

Most profile content is centralized in `src/profile.js`. Update:
- About text
- LinkedIn / GitHub / email
- Projects and tech stacks
- Achievements
- Education and timeline
- Skills

The design, responsive layout and theme switcher live in `src/styles.css` and `src/main.jsx`.

## Notes

The LinkedIn page could not be directly fetched during generation, so this version uses the profile/project information available in the provided context. Replace any details that differ from your live LinkedIn profile in `src/profile.js`.
