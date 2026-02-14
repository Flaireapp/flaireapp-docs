<h1 align="center">Flaire Documentation</h1>

This repository powers the public docs for the Flaire creator-brand collaboration platform. It is built with [Mintlify](https://mintlify.com) and deployed automatically on every merge to `main`.

## Getting started
1. Install dependencies
   ```bash
   npm install -g mintlify
   ```
2. Run the local server
   ```bash
   mintlify dev
   ```
3. Open [http://localhost:3000](http://localhost:3000) to preview the docs with hot reload.

## Writing guidelines
- Each tab (Brands / Creators) should tell a complete story on its own.
- Prefer actionable steps, tables, and callouts over marketing language.
- Keep titles in sentence case and include concise descriptions in the frontmatter.
- Reference internal pages using relative links (e.g., `/creator-workflows/cw1`).

## Contributing
1. Create a branch following the pattern `docs/<topic>`.
2. Make your changes and run `mintlify lint` before opening a PR.
3. Request review from the Docs or Product team.

## Support
Questions? Contact the Flaire documentation team at [docs@flaireapp.co](mailto:docs@flaireapp.co).
