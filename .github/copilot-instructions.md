# Artifact Analysis Results — Copilot Instructions

## This Repository is 100% Auto-Generated

All files in `output/` are produced by the
[reprodb-pipeline](https://github.com/reprodb/reprodb-pipeline) pipeline
and committed via GitHub Actions monthly. **Do not manually edit any generated files.**

To update data, re-run the pipeline — do not patch files directly.

## Structure

- **`output/artifacts.json`** — full artifact listing (primary output)
- **`output/charts/`** — pre-generated SVG visualizations
- **`output/website_data/`** — archived copy of website `_data/` and `assets/`
- **`input/dblp_checksum.txt`** — DBLP XML integrity hash for reproducibility
- **`input/run_metadata.txt`** — pipeline arguments and configuration

## Purpose

This repo serves as an immutable archive of pipeline runs. Each commit represents
a point-in-time snapshot enabling:

- Historical diffing of artifact data across runs
- Reproducibility verification via input checksums
- Data recovery if the website repo diverges
