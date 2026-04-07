# Artifact Analysis Results

This repository records the input, intermediate (cache), and output data from each pipeline run of [reprodb/reprodb-pipeline](https://github.com/reprodb/reprodb-pipeline).

Each commit represents a single pipeline run snapshot, allowing reproducible re-analysis based on the same underlying data.

## Structure

```
cache.tar.gz        # Tarred HTTP and API response caches (namespaced)
output/
  data.tar.gz       # Tarred YAML + JSON data files (_data/*.yml, assets/data/*.json)
  charts/           # Generated SVG visualizations (individual files for easy diffing)
input/
  dblp_checksum.txt # SHA-256 of the DBLP XML used (empty if not available)
  run_metadata.txt  # Git revisions, timestamps, cache version
```

