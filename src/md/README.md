# srcmd.org

srcmd.org is a static site on GitHub Pages. It suggests a simple layout for storing the intent of code as Markdown next to the code.

## Stack

- The site is plain HTML and CSS.
- The project has no build tool, CI, or JavaScript.
- GitHub Pages publishes the `docs/` folder from the main branch.

## Files

- `docs/index.html`: the home page, with inline styles
- `docs/srcmd.svg`: the logo and favicon
- `docs/.nojekyll`: stops the Jekyll step on GitHub Pages
- `docs/CNAME`: the custom domain
- `src/md/`: the intent of this site
- `tmp/`: plans and TODOs, not checked in

## Rules

- Change `src/md` first, then change the site files.
- To add a page, add one `.html` file to `docs/`.
- Only `docs/` is published.
- Use STE (ASD-STE100 Simplified Technical English) for all files in `src/md`.

## File Index

- [features/spec-page.md](features/spec-page.md): home page
- [features/example.md](features/example.md): src/md example
