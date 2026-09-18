# Supplementary Material

**[`Supplementary_Material_final.pdf`](Supplementary_Material_final.pdf)** — 3 pages, Tables S1–S3.

Accompanies: J. Cheng, B. Chen, Z. Wang, X. Ye, R. Cheng, and T. Wang, "WP-M<sup>2</sup> Net:
Wavelet-Perception Macro-Micro Dynamic 1D-CNN for Efficient Sequential Motion Recognition from Sparse
sEMG," *IEEE Journal of Biomedical and Health Informatics*, 2026,
doi: [10.1109/JBHI.2026.3734535](https://doi.org/10.1109/JBHI.2026.3734535).

Identical to the file submitted with the accepted manuscript.

## Contents

**Part I — Experimental configuration and evaluation protocols** (Table S1)

| Panel | Scope |
|---|---|
| A | Datasets, input tensors, filtering, normalization, per-dataset W-MP decomposition levels |
| B | Architecture: stem, four-stage pyramid, W-MP/MA kernels, SE and FFN widths, dropout, head |
| C | Optimization: Adam, LR schedule, early stopping, loss, augmentation, checkpoint selection |
| D | Data partitioning, intra- and inter-subject protocols, CPU latency measurement |

**Part II — Statistical analysis** (Table S2)

| Panel | Scope |
|---|---|
| A | Descriptive accuracy for all six dataset/protocol combinations and the statistical role of each |
| B | Nine paired participant-level comparisons per dataset, with effect sizes and Holm-adjusted *p* |

**Part III — Robustness to simulated signal degradation** (Table S3)

Formal definitions (Eqs. 1–8) and fixed operator parameters for four conditions applied before inference
to a fixed trained model, without retraining:

| Condition | Datasets | Severity |
|---|---|---|
| Random channel masking | RAS-KP, ADSE | *m* ∈ {0,…,5} (RAS-KP); {0,…,4} (ADSE) |
| Random temporal masking | RAS-KP, ADSE | *q* ∈ {0, 0.05, …, 0.50} |
| Simulated motion artifacts | RAS-KP | *ρ* ∈ {0, 0.1, …, 1.0} |
| Simulated muscle fatigue | RAS-KP | *ρ* ∈ {0, 0.1, …, 1.0} |

---

© IEEE. Please cite the published article and observe the IEEE reuse policy.
