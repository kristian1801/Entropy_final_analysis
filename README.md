# Entropsy: Final Analysis Code

## Overview

This repository contains the complete analysis code for the **Entropsy** project, which investigates psychedelic-specific effects on brain entropy and complexity measures.

## Contents

All analyses are contained in a single script that includes both whole-brain and multi-metric analyses.

### Whole-Brain Measures

- Lempel-Ziv complexity
- Modularity
- Meta-state complexity
- Whole-brain normalised spatial component entropy

### Multi-Metric Measures (Network-Level)

- Multiscale sample entropy (scale 1 and scale 5)
- Network-level normalised spatial component entropy
- Dynamic conditional correlation entropy

## Deviation from Preregistered Analysis Plan

The following change was made from the original analysis plan (available in a separate repository):

- **Multiple comparisons correction**: Changed from Dunnett's test to Holm-Bonferroni method to control Type I error rate across all outcome measures in the analysis.

## Related Repository

The preregistered analysis plan with synthetic data validation can be found at: https://github.com/kristian1801/entropsi_planned_analysis_february_2025
