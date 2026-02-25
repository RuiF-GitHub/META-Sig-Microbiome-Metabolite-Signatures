
---
layout: default
title: Workflow overview
nav_order: 3
---

# Workflow overview

This page summarizes META‑Sig's end-to-end pipeline. Replace details with your implementation.

## Inputs
- Untargeted LC–MS(/MS) feature table (mz, rt, intensity)
- Sample metadata (study design, batches, covariates)
- (Optional) Microbiome profiling (16S/shotgun), MAGs, or functional profiles

## Processing stages
1. **Quality control**: missingness thresholds, blank subtraction, batch correction
2. **Feature grouping**: adduct/fragment/isotope collapsing
3. **Annotation & identification**: spectral library matching; in‑silico predictions where applicable
4. **Context mapping**: pathways/ontologies (e.g., KEGG, HMDB); mapping to microbial pathways if available

## Microbial attribution
- **Signature-based**: presence in microbial cultures, known microbial pathways
- **Covariation**: correlation with microbiome taxa/functions across samples
- **Perturbation**: enrichment under microbiome-modulating conditions (ABX, FMT, gnotobiotic models)
- **Evidence scoring**: combine orthogonal evidence to rank candidates

## Outputs
- Ranked candidates with:
  - ID/annotation level
  - Evidence sources (signature, covariation, enrichment)
  - Confidence score
  - Links to spectra and references
