# resume

Data-driven resume built with [RenderCV](https://rendercv.com) (YAML -> Typst PDF).

## Usage

```sh
uv tool install "rendercv[full]"
rendercv render samuel-mohr-resume.yaml
```

Output lands in `rendercv_output/` — the PDF is committed, the rest regenerates.

## Files

- `samuel-mohr-resume.yaml` — single source of truth (content, design, locale)
- `rendercv_output/samuel-mohr-resume.pdf` — generated PDF (committed)

RenderCV is pinned to v2.8 (schema URL is in the YAML header comment).
