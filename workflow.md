


# Workflow overview

This page summarizes META‑Sig pipeline.

## Inputs
- Untargeted/targeted LC–MS(/MS) table (metobolites per sample)
- Sample metadata (study design, batches, covariates) - optional
- Microbiome metatranscriptomics profiling table (UniRef90 gene families per sample)

## Processing stages
- Filter low prevelance UniRef90 gene families (<5%)
- Filter metabolites with ambigous names

## Microbial attribution
- **Signature-based**: presence in microbial cultures, known microbial pathways
- **Covariation**: correlation with microbiome taxa/functions across samples
- **Perturbation**: enrichment under microbiome-modulating conditions (ABX, FMT, gnotobiotic models)
- **Evidence scoring**: combine orthogonal evidence to rank candidates

## Outputs
- Ranked candidates with:
  - A table with relative abundance of metabolites attribute to microbial orign per sample
  - If sample metadata are provided, it produces a table with metabolite differential abundance analysis. User must set the grouping varaible.
