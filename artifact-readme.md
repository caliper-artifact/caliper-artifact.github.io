# CALIPER Artifact Summary

The canonical anonymous CALIPER artifact is hosted at:

- GitHub artifact repository: https://github.com/caliper-artifact/caliper-artifact
- Hugging Face dataset mirror: https://huggingface.co/datasets/caliper-artifact/caliper-artifact

This Pages repository hosts only the static explorer website. It includes the web interface plus compact site data needed for browser-side ranking, search, and prompt analysis.

## Canonical Artifact Layout

```text
prompts_paraphrases/
paraphrase_answers/
metric_scores/
responses/
scores/
samples/
figures/
site_data/

code/
  preprocessing/
  inference_scoring/
  analysis/
  explorer/

caliper_croissant_rai.json
asset_licenses.md
anonymous_artifact_readme.md
manifest.json
code.zip
```

## Main Files

- `prompts_paraphrases/`: canonical prompt/paraphrase files and style tags.
- `paraphrase_answers/`: model generations for Alpaca, GSM8K, and MMLU.
- `metric_scores/`: response-quality metric score files for evaluated generations.
- `responses/` and `scores/`: merged response and aggregate scoring outputs.
- `samples/`: compact samples for quick inspection.
- `site_data/`: data bundles used by the CALIPER Explorer.
- `code/`: preprocessing, generation, scoring, analysis, and explorer code.
- `code.zip`: zipped copy of the submitted code tree.
- `caliper_croissant_rai.json`: Croissant and Responsible AI metadata.
- `asset_licenses.md`: license and version manifest for source datasets, evaluated models, and generated artifacts.

## Scoring Provenance

All reported automated content-preservation and task-performance scores used `gemini-2.5-flash-preview-05-20` as the judge model. Scoring was run in September 2025 with deterministic decoding, temperature 0, and fixed system instructions.

## Terms

This is a mixed-license artifact. CALIPER-authored code, metadata, and documentation use Apache-2.0. Redistributed or prompt-derived records preserve the upstream source dataset licenses and evaluated model-provider terms. See `asset_licenses.md` in the canonical artifact repository for exact license and version strings.
