# macrorun-legal

Static site for [macrorun.tablefourapps.com](https://macrorun.tablefourapps.com), served by GitHub Pages.

## Generated files: do not hand-edit

`terms/index.html` and `privacy/index.html` are generated from `tablefourapps/MacroRun` `docs/store/*.html` (built from `src/lib/legal.ts`). They must be byte-for-byte identical to the in-app legal pages and must never be hand-edited here. To change them, edit `src/lib/legal.ts` in MacroRun, regenerate `docs/store/terms.html` and `docs/store/privacy.html`, and copy those files over unchanged:

- `docs/store/terms.html` → `terms/index.html`
- `docs/store/privacy.html` → `privacy/index.html`
