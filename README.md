# ignite-goober

Single-file builds of [Ignite OS](https://igniteos.org) served over unpkg.

## Load via unpkg

Pinned to a version:

```
https://unpkg.com/ignite-goober@1.0.0/index.html
https://unpkg.com/ignite-goober@1.0.0/index.svg
```

Latest:

```
https://unpkg.com/ignite-goober/index.html
https://unpkg.com/ignite-goober/index.svg
```

## What's inside

- `index.html` — single-file HTML build (JS and essential images inlined, non-essential images under `imgs/`).
- `index.svg` — SVG-wrapped build that renders the whole app inside a `<foreignObject>`.
- `imgs/` — non-essential images referenced by both builds as `./imgs/…`.
