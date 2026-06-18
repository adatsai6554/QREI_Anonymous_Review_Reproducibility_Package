# Anonymous Review Reproducibility Package

This repository provides an anonymized reproducibility package for reviewer verification of a manuscript on label-governed rough-set and data-depth screening control charts for cost-sensitive semiconductor quality monitoring.

## Contents

The package includes:

- cross-validation split indices
- fold-wise preprocessing masks
- PCA outputs
- rough-set reduct outputs
- data-depth scores
- lower control limits
- PCA-Hotelling T-squared scores and thresholds
- test predictions
- fold-level metrics
- table and figure input files
- review checklist and README mapping files

## Dataset

The study uses the public UCI SECOM dataset. The dataset is treated as a high-dimensional, missing-value, low-defect-prevalence benchmark for retrospective Phase-I-like reference construction. It is not treated as a sequential fab deployment dataset.

## Review Use

This repository is provided for reviewer verification and reproducibility checking. It is not intended to disclose author identity during review.

## Important Boundary

The workflow is label-governed rather than fully label-free. Rough set theory uses the decision attribute for sensor-code reduct construction, while data-depth and PCA-Hotelling T-squared thresholds are estimated from training-good observations only. Test-fold labels are used only for DDR, FAR and ECM evaluation.

## Archiving

The repository or its contents will be archived publicly with author information after acceptance, subject to journal policy.
