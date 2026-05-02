# tooluse-labs/.github

Org-level configuration and assets for [Tooluse Labs](https://github.com/tooluse-labs).

## Contents

- **`profile/README.md`** — the README rendered on https://github.com/tooluse-labs (the org profile page).
- **`assets/brand/`** — canonical source files for the org avatar / logo. Update once here, re-upload to GitHub org settings + Glama + any other place the avatar is consumed.

## Brand assets

| File | Purpose |
|---|---|
| `assets/brand/avatar.svg` | Source of truth (vector). Edit this, then re-render PNGs. |
| `assets/brand/avatar-1024.png` | High-res raster for GitHub org Settings → Profile picture (recommended upload). |
| `assets/brand/avatar-460.png` | Fallback raster for places that prefer a smaller upload. |
| `assets/brand/avatar-circle-preview.png` | Reference image showing how the avatar renders after GitHub's circular crop. Not for upload. |

To regenerate the PNGs after editing `avatar.svg`:

```sh
python -c "import cairosvg; cairosvg.svg2png(url='assets/brand/avatar.svg', write_to='assets/brand/avatar-1024.png', output_width=1024, output_height=1024)"
python -c "import cairosvg; cairosvg.svg2png(url='assets/brand/avatar.svg', write_to='assets/brand/avatar-460.png', output_width=460, output_height=460)"
```

## Avatar design rationale

The mark is `[ ··· ]` — square brackets enclosing three dots — reading as the function-call notation `tool(args)` that the org's name "Tooluse" alludes to.

- **Cyan** `#5EEAD4` brackets — neutral against the AI-tooling brand landscape (Anthropic uses burnt orange, OpenAI black/white, Hugging Face yellow), gives a distinct visual fingerprint.
- **Amber** `#F5A623` dots — warm focal accent, visible at favicon size where the brackets blur.
- **Dark** `#0E1618` background with `rx=48` rounded corners — works under GitHub's circle crop without odd geometry.

Bracket inner-edge gap is intentionally wide (`x=60` to `x=196` on a 256-unit canvas) so the composition reads more like an actual function-call slot than a tight ellipsis. Verified to survive GitHub's circular avatar crop.
