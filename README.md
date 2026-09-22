# Praxis Dr. Weiss

Landing page for a dental practice in Munich. Built with Astro and Tailwind CSS.

**Live:** [praxis-dr-weiss-demo.vercel.app](https://praxis-dr-weiss-demo.vercel.app)

## Stack

| Layer      | Technology     |
| ---------- | -------------- |
| Framework  | Astro 7        |
| Styling    | Tailwind CSS 4 |
| Deployment | Vercel         |

## Structure

```
src/
├── components/   Header.astro, Footer.astro
├── layouts/      Layout.astro — page shell, meta tags
├── pages/        index, impressum, datenschutz
└── styles/       global.css — Tailwind entry point
```

## Getting Started

```bash
npm install
npm run dev
```

The site runs at `http://localhost:4321`.

## Scripts

| Command           | Description                   |
| ------------------ | ------------------------------ |
| `npm run dev`      | Start the dev server           |
| `npm run build`    | Build for production           |
| `npm run preview`  | Preview the production build   |

## Notes

`/impressum` and `/datenschutz` currently hold placeholder text and need a legal review with real business data before going live.
