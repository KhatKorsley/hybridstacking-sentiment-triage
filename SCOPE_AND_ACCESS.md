# Restricted Code-Inspection Package

## Purpose

Documenting the analysis code, methodological sequence, and privacy-reviewed aggregate outputs supporting the Banjarbaru sentiment-classification manuscript. It is intended for code inspection and traceability of the reported results.

## Access Boundary

This package does not include the Banjarbaru source dataset, processed review data, business-level metadata, manual-audit records, row-level predictions, probability vectors, model checkpoints, vocabularies, tokenizer caches, or bootstrap replicate files. It is therefore not an independently runnable full-data reproduction package.

The notebooks describe the original workflow and may refer to authorized inputs that remain outside this package. Access to those inputs is governed separately by the data custodian and applicable source-data restrictions.

## Included Material

- Cleaned notebook copies with English Markdown explanations.
- A privacy-reviewed aggregate-output directory supporting the manuscript and supplementary material.
- A release manifest mapping each shared artifact to its source analysis stage.
- A notebook sequence beginning with `notebooks/00_scope_and_data_contract.ipynb`.

## Excluded Material

No raw review text, place identifiers, addresses, coordinates, audit identifiers, annotation sheets, record-level predictions, model binaries, or private quality-assurance artifacts are distributed.


