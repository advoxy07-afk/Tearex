# TeaRex Menu Hub

A responsive Tea Rex Café menu and visit-information website built with React, TanStack Start, and Tailwind CSS.

## Features

- Responsive café landing page and menu browsing
- Menu data centralized in `src/lib/menu.ts`
- Location, directions, gallery placeholders, and review section
- Accessible loading, error, and empty-state handling

## Requirements

- Node.js 22 or newer
- npm 10 or newer

## Development

```sh
npm install
npm run dev
```

## Validation

```sh
npm run lint
npm test
npm run build
```

## Google Maps and reviews

The current map uses a Google Maps embed and outbound links. It does not claim to provide live Google Places reviews or photos. If live Places data is added later, keep API credentials in server-side environment variables and never commit secrets to the repository.
