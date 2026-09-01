# GExMix

> **Status: Unpublished / Work in Progress**
> This repository accompanies research that has not yet been peer-reviewed or formally published. Code is not currently public. See [Access](#access) below.

## Overview

GExMix is a model-agnostic framework for augmenting molecular patient data through controlled, label-aware interpolation, designed to improve clinical drug response prediction in data-limited settings. This work was presented as a poster at [Conference Name / Venue], [Month Year].

## Motivation

Clinical drug response prediction is constrained by small patient cohorts, biological heterogeneity, and imbalanced treatment responses. Most methodological progress in this space has focused on predictive models, while data augmentation strategies for molecular patient data remain comparatively underexplored. GExMix addresses this gap with a systematic, data-centric augmentation approach.

## Key Results

Evaluated across three clinical cohorts, five anticancer drugs, and six predictive architectures, GExMix:
- Outperforms established augmentation strategies, with average relative improvements of **5.7% in ROC-AUC** and **6.3% in AUPRC**
- Shows the largest gains in smaller patient cohorts, and generalizes across both machine-learning and deep-learning architectures
- Preserves molecular manifold structure and response-associated biological signals, indicating predictive gains do not come at the cost of biological consistency
- Yields an additional **4–6% improvement** when integrating preclinical data, for drugs with transferable response information (benefits vary by drug and diminish in models with strong intrinsic regularization)

## Data

This project uses publicly available clinical cohort and drug response datasets:
- TCGA
- CCLE

Note: while the datasets used are public, the augmentation method implemented in this repository is part of ongoing, unpublished research.

## Access

The full codebase is currently **private** while the associated manuscript is in preparation. It will be made public upon publication.

If you are interested in:
- collaborating,
- reviewing the method ahead of publication, or
- citing/building on this work,

please reach out directly: **daksh.pamar@student.unimelb.edu.au** 

## License

To be determined upon publication. Please do not reuse, redistribute, or replicate the method described without permission until then.

## Contact

Daksh Pratap Singh Pamar
University of Melbourne
daksh.pamar@student.unimelb.edu.au
https://biomedicalsciences.unimelb.edu.au/sbs-research-groups/biochemistry-and-pharmacology-research/menden-laboratory
