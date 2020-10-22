# Gene Set Enrichment Control

This repository contains positive controls from various gene set enrichment experiments.

A control is a directory:

```
experiment_name
├── gene_set.json
├── gene_x_sample.tsv
└── sample_group.tsv
```

Names use only lowercase letter, number, and underscore.

### gene_set.json

```json
{
  "gene_sets_tested": ["file/path/to/a.gmt", "file/path/to/another.gmt"],
  "gene_sets_positive": ["jack_signaling", "kwat_signaling"]
}
```
