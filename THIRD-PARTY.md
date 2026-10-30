# Third-party notices

Slate ships no runtime dependencies and no build step.

| Component | Version | License | Use |
|---|---|---|---|
| Node.js | >= 20 | MIT-style (Node.js license) | Runtime for the local server only; not bundled |
| Chrome / Edge | any current | Proprietary | Used only by the optional screenshot/proof scripts through the DevTools Protocol |

Fonts are the system faces Georgia, Palatino Linotype, Book Antiqua and Consolas — no font files
are distributed with this repository. Icons are hand-written inline SVG. The paper-grain texture is
an inline SVG `feTurbulence` filter authored for this app.

`package.json` has no `dependencies` and no `devDependencies`; `npm install` creates nothing and
`npm run selftest` requires no network access.
