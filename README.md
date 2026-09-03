# resume

Data-driven resume built with [RenderCV](https://rendercv.com) (YAML -> Typst PDF).

## Usage

```sh
uv tool install "rendercv[full]"
rendercv render Samuel_Mohr_CV.yaml
```

Output lands in `rendercv_output/` — the PDF is committed, the rest regenerates.

## Files

- `Samuel_Mohr_CV.yaml` — single source of truth (content, design, locale)
- `rendercv_output/Samuel_Mohr_CV.pdf` — generated PDF (committed)

RenderCV is pinned to v2.8 (schema URL is in the YAML header comment).
