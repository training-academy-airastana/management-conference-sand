# Air Astana Group Management Conference — Sand

Style variant of the XVIII Management Conference website, 3 December 2026.
The event content, three agenda views, navigation and speaker dialogs are shared with the main implementation.

## Run locally

```sh
npm ci
npm run dev
```

## GitHub Pages

The included workflow builds a Next.js static export and deploys it with GitHub Actions.
The repository name supplies the Pages base path automatically.

Update confirmed links and forthcoming copy in `data/siteConfig.ts`.
The 14:00 quiz and 14:15 panel overlap is retained from the supplied agenda.
Brand asset sources are recorded in `public/fonts/SOURCES.txt`.
