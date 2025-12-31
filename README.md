# alphagenome-splicing-VPS35L

This repository contains the code used to perform AlphaGenome-based splicing predictions for the VPS35L c.881T>C (p.Phe294Ser) variant reported in the associated manuscript.

## Overview
AlphaGenome was used to generate reference and alternate allele predictions for RNA-related outputs, including splice site usage, RNAseq and splice junction signals. Visualizations include per-base splicing tracks and sashimi plots.

## Execution environment
Analyses were performed using the official AlphaGenome notebook environment (Google Colaboratory). Due to controlled access, users must obtain valid AlphaGenome API credentials to execute the notebook.

## Reproducibility
The notebook documents all analysis steps, including:
- variant and interval definition
- tissue specification via UBERON ontology terms
- splicing signal visualization
- figure generation

Outputs are intended as hypothesis-generating computational evidence and should be interpreted in conjunction with orthogonal splicing predictors and/or experimental validation.
