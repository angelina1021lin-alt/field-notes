# field-notes
An interactive photography archive

## Tech stack

- [Next.js](https://nextjs.org) (App Router) with TypeScript
- [Tailwind CSS](https://tailwindcss.com) for styling
- Planned: MapLibre GL JS (world map) and React Flow (evidence board)

## Getting started

You need [Node.js](https://nodejs.org) installed (v20 or newer).

```bash
# 1. Install dependencies (only needed once, or after package.json changes)
npm install

# 2. Start the development server
npm run dev
```

Then open http://localhost:3000 in your browser. The page reloads automatically when you edit files.

## Useful commands

| Command         | What it does                                  |
| --------------- | --------------------------------------------- |
| `npm run dev`   | Start the local development server            |
| `npm run build` | Create an optimized production build          |
| `npm run start` | Run the production build (after `build`)      |
| `npm run lint`  | Check the code for common mistakes            |

## Project structure

```
app/          Pages and layouts (App Router)
  layout.tsx  Shared layout wrapping every page
  page.tsx    The home page (/)
  globals.css Global styles and Tailwind import
public/       Static files served as-is (images, icons)
```
