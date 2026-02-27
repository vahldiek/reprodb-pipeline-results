# Artifact Analysis Results

This repository records the input, intermediate (cache), and output data from each pipeline run of [researchartifacts/artifact_analysis](https://github.com/researchartifacts/artifact_analysis).

Each commit represents a single pipeline run snapshot, allowing reproducible re-analysis based on the same underlying data.

## Structure

```
cache.tar.gz        # Tarred HTTP and API response caches (namespaced)
output/
  data.tar.gz       # Tarred YAML + JSON data files (_data/*.yml, assets/data/*.json)
  charts/           # Generated SVG visualizations (individual files for easy diffing)
input/
  dblp_checksum.txt # SHA-256 of the DBLP XML used
  pipeline_args.txt # Arguments passed to the pipeline
  pipeline.log      # Pipeline stdout/stderr
  run_metadata.txt  # Git revisions, timestamps, cache version
```

