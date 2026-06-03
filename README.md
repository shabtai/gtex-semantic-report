# GTEx Annotations — Semantic Enrichment & Data-Bug Report

A live, auto-generated report over two public **GTEx v8** annotation tables
(`SampleAttributesDS`, `SubjectPhenotypesDS`). An LLM-agent pipeline
([Semantic Enricher](https://github.com/)) resolved the meaning of all 67 cryptic
columns, then hunted for the data traps and row-level wrong values that silently
break analysis.

**👉 Live page: https://shabtai.github.io/gtex-semantic-report/**

- 67 columns auto-resolved (100%) across 22,951 biospecimen rows / 980 donors
- 1 hard FAIL, 55 curated column-shape traps, 44 row-level wrong values
- Every finding carries its evidence and a concrete fix

Findings are automated and may include false positives.
