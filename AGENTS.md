# AGENTS.md

## Cursor Cloud specific instructions

This is a zero-dependency static HTML portfolio site (single `index.html` with inline CSS and vanilla JS). There are no package managers, build tools, linters, or test frameworks.

### Running the dev server

Serve the site with any static HTTP server from the repo root:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/` in Chrome.

### Key notes

- The page loads Google Fonts and an Unsplash image via CDN; internet access is required for full visual fidelity.
- All CSS and JavaScript is inline in `index.html` — there is nothing to build or compile.
- There are no automated tests, linters, or CI pipelines configured in this repository.
- The scan beam animation, ping markers, and LED status widget cycle automatically on page load — wait ~6 seconds after load to see all animations fire.
