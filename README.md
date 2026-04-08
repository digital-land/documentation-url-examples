# Documentation URL examples
 
These pages show example patterns for how a local planning authority might publish planning data on their website. They are only a guide — you don't have to replicate them exactly.
 
[View the examples](https://digital-land.github.io/documentation-url-examples/)
 
## About
 
The examples are built as plain HTML files and served via GitHub Pages. No build step is required.
 
The fictional West Brackenfield District Council is used throughout as the example local planning authority.
 
## Files
 
| File | Description |
|---|---|
| `index.html` | Start page — overview of the four patterns |
| `all-on-one-page.html` | Pattern 1 — all records on one page with anchor links |
| `one-per-page.html` | Pattern 2 — index page linking to individual record pages |
| `a4d-001-brackenfield-old-town.html` | Individual record page (example) |
| `a4d-002-fenwick-road.html` | Individual record page |
| `a4d-003-stonemoor-lane.html` | Individual record page |
| `a4d-004-holt-green.html` | Individual record page |
| `a4d-005-thornwick-business-park.html` | Individual record page |
| `a4d-006-millgate-riverside.html` | Individual record page |
| `finder.html` | Pattern 3 — searchable, filterable finder with URL-based pagination |
| `west-brackenfield-local-plans.html` | Pattern 4 — complex datasets example (Local Plans) |
 
## Viewing locally
 
Because the site is plain HTML, you can open any file directly in your browser — no server or build step needed.
 
If you prefer to serve it locally (for example to test links between pages):
 
```bash
npx serve .
```
 
Then open `http://localhost:3000` in your browser.
 
## Deployment
 
Pushes to `main` are automatically deployed to GitHub Pages via the workflow in `.github/workflows/deploy.yml`.
