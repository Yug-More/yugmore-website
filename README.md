# Yug More

Source for the portfolio at [yug-more.github.io](https://yug-more.github.io/).

## Layout

- `app/` — page, layout, and styles
- `components/layout/` — navigation, footer, and section frame
- `components/sections/` — page sections
- `lib/` — site content and links
- `public/` — portrait and static files

## Develop

```bash
npm install
npm run dev
```

## Checks

```bash
npm run lint
npm run typecheck
npm run build
```

Set `NEXT_PUBLIC_SITE_URL` to the production origin when you deploy, so canonical and social metadata resolve to absolute URLs.
