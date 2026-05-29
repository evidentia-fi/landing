# Evidentia Landing

Static landing page for Evidentia, built with Astro.

## Requirements

- Node.js `>=22.12.0`
- npm

## Development

Install dependencies:

```sh
npm install
```

Start the local dev server:

```sh
npm run dev
```

Astro will print the local URL, usually `http://localhost:4321/`.

## Build

Create a production static build:

```sh
npm run build
```

The generated site is written to `dist/`.

Preview the production build locally:

```sh
npm run preview
```

## Project Structure

```text
/
├── public/
│   ├── fonts/
│   ├── tokens/
│   ├── bg-home.webp
│   ├── bg-contact-us.webp
│   └── docs.html
├── src/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Notes

- Fonts are self-hosted from `public/fonts/`.
- Token/network icons are stored in `public/tokens/`.
- `public/docs.html` is copied directly into the static build.
