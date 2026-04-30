# Intron Variant Effect Comparison: In Vitro vs AlphaGenome vs SpliceAI
Systematic comparison of intronic variant effects across in vitro assays and computational predictions (AlphaGenome, SpliceAI). This repository provides a curated dataset of 672 variants, analysis of concordance and discrepancies, and a framework for community-driven interpretation and model evaluation.

## Overview
This repository contains a systematic comparison of 672 genetic variants
across:
- in vitro experimental data
- AlphaGenome predictions
- SpliceAI predictions

## Motivation
Predictive models are widely used, but discrepancies with experimental
data remain insufficiently characterized.

## Dataset
- 672 variants
- Source: Dataset comprises 672 intronic variants tested in vitro using splicing reporter assays. Variants were selected from patients with confirmed genetic condition and based on allele frequency (MAF<0.001), experimentally evaluated to quantify effects on RNA processing and predicted impact from computational tools (AlphaGenome, SpliceAI) 
- Experimental system: HEK293 cells

## Goals
- Identify agreement/disagreement patterns
- Highlight systematic biases
- Engage community interpretation

## Call for contributions
We welcome discussion, alternative interpretations, and additional datasets.

## Methods

A detailed description of experimental design and analysis is available in:
[Methodology](docs/methodology.md)

intron-variant-effect-comparison/
│
├── README.md
├── LICENSE
├── CITATION.cff
│
├── data/
│   ├── raw/
│   │   └── variants_672_original.xlsx
│   ├── processed/
│   │   └── variants_672_cleaned.csv
│
├── results/
│   ├── figures/
│   ├── tables/
│   └── summary_statistics.csv
│
├── analysis/
│   ├── notebooks/
│   │   └── analysis.ipynb   (optional, even later)
│   └── scripts/             (optional)
│
├── docs/
│   ├── methodology.md
│   ├── interpretation.md
│   └── discrepancies.md
│
└── community/
    ├── discussion_guidelines.md
    └── known_issues.md
