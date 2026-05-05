# CALIPER Explorer Website

Hosted site: https://caliper-artifact.github.io/

This repository is the GitHub Pages site for the anonymous CALIPER artifact.

It serves a static browser explorer built from `code/explorer/` in the artifact release. The site uses compact prompt examples plus precomputed aggregate metric bundles so GitHub Pages remains lightweight while the rankings and recommendations reflect the full artifact metrics. The full CALIPER dataset and code release should remain available through the canonical artifact repository:

- Hugging Face dataset: https://huggingface.co/datasets/caliper-artifact/caliper-artifact
- GitHub code/artifact repository: https://github.com/caliper-artifact/caliper-artifact

## Local Preview

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages

Create this repository as `caliper-artifact/caliper-artifact.github.io` and push the contents of this directory to `main`. GitHub Pages will serve it at:

https://caliper-artifact.github.io/
