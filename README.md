This repository contains positive controls from various gene set enrichment experiments.

A control is a directory:

```
experiment_name
├── comparison_x_sample.tsv
├── gene_x_sample.tsv
└── gene_set.json
```

Names use only lowercase letter, number, and underscore.

`comparison_x_sample.tsv`

1 row

N sample columns

`gene_x_sample.tsv`

N gene rows

N sample columns

`gene_set.json`

```json
{
  "gene_sets_tested": ["file/path/to/a.gmt", "file/path/to/another.gmt"],
  "gene_sets_positive": ["jack_signaling", "kwat_signaling"]
}
```
