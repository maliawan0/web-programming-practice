# Web Programming Practice

Vanilla HTML, CSS and JavaScript exercises from my Web Programming course — no frameworks, no build step. Open any file in a browser and it runs.

## What's in here

| File | What it is |
|---|---|
| [`cvGenerator.html`](cvGenerator.html) | Form-driven CV builder — fill in details, get a formatted CV |
| [`movieclone.html`](movieclone.html) | Streaming-service UI clone (Netflix-style landing page) |
| [`pokemon.js`](pokemon.js) | Pokémon browser built against the public PokéAPI — fetch, render, search |
| [`index.html`](index.html) | Entry page linking the exercises |
| `first.html` … `sixth.html` | Progressive exercises — layout, forms, flexbox/grid, DOM manipulation |
| `first.css`, `first.js` | Shared styling and script for the numbered exercises |

## Topics covered

Semantic HTML · CSS layout (flexbox, grid, positioning) · responsive design · DOM manipulation · event handling · `fetch` and async JavaScript · consuming a public REST API

## Running it

No dependencies and no build. Either open a file directly:

```bash
start index.html      # Windows
```

or serve the folder if you want the API calls to run over `http://` rather than `file://`:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
