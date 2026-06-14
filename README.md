# Nickname Generator

A small full-stack web app that generates 1000+ random nicknames by pairing an
adjective with a noun (e.g. `impractical-kneejerk`). Built with Express and EJS
while learning server-side rendering.

## Run locally

```bash
npm install
npm start
```

Then open <http://localhost:3000> and hit **Generate**.

## How it works

- `index.js` — Express server. `POST /submit` picks a random adjective + noun and
  renders the result; `GET /` shows the landing page.
- `views/` — EJS templates (`index.ejs` plus header/footer partials).
- `public/` — static CSS and JS.

## Stack

Node.js · Express · EJS · body-parser
