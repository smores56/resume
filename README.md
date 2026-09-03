# resume

Data-driven resume built with [RenderCV](https://rendercv.com) (YAML -> Typst PDF).

## Usage

```sh
uv tool run "rendercv[full]" render Samuel_Mohr_CV.yaml
```

## Files

- `Samuel_Mohr_CV.yaml` — single source of truth (content, design, locale)
- `rendercv_output/` — generated PDF (+ Markdown/HTML/PNG)

## Tooling

- RenderCV pinned: see `.rendercv-version` / `pyproject.toml` if applicable
