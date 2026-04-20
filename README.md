# A-collection-of-practical-scripts-for-compositional-data-analysis
The Definitive Compositional Data Analysis (CoDA) Engine for Microbiome &amp; Nutritional Research. Implements the Triple Stability Engine, Quad-Basis Triangulation, and Subcompositional Coherence testing (V17.0/V36.5) based on Ohta (2011) and Itagaki (2024-2026) logics.
# ITAGAKI-SYSTEM (V8.0 - V36.5)
## Rigorous Framework for Compositional Data Analysis and Quantitative Reconstruction

ITAGAKI-SYSTEM is a generalized analytical framework designed to strictly adhere to the mathematical principles of Compositional Data Analysis (CoDA). It enables the reconstruction and validation of absolute physical dynamics from relative abundance constraints by integrating external information, specifically physical noise floors and temporal sequences.

---

### 1. Analytical Logic & Engines

#### ■ ITAGAKI-CHAOS-ENGINE (V8.0)
Diagnoses the stability of compositional systems through three independent mathematical bases:
- **Physical ($S_p$):** Evaluation of variance invariance (Invariance Ratio) relative to the physical noise floor (Effective Library Size).
- **Geometric ($S_g$):** Calculation of geometric entropy via eigenvalue decomposition within the Aitchison Simplex.
- **Statistical ($S_s$):** Identification of stable anchors and component asymmetry based on Ohta’s (2011) logic.

#### ■ QUANTITATIVE RECOVERY GATEWAY (V10400.0)
A definitive protocol for reconstructing absolute scale changes from relative datasets:
- **Quad-Basis Triangulation:** Multi-validation using the Geometric Centroid and three high-stability anchors.
- **Monotonicity & SNR Filter:** Cross-references temporal information with absolute SNR (Signal-to-Noise Ratio) to extract true growth signals independent of compositional bias.

#### ■ SUBCOMPOSITIONAL COHERENCE ENGINE (V17.0)
Validates "Subcompositional Invariance," a core principle of Aitchison geometry:
- **Component Stripping:** Tests whether the structural signal (CLR variance/rank) remains invariant after removing volatile components, ensuring the robustness of the analytical conclusion.

#### ■ SPATIO-TEMPORAL TRAJECTORY (V25.0 - V36.5)
- **Subject-linked PCA Trajectory:** Mapping trajectories in Aitchison space linked by Subject ID and chronological order.
- **Anti-Collision Engine:** A high-definition rendering system for dense Loadings, utilizing variance-weighted scaling and dynamic jitter to prevent label overlap.

---

### 2. General Principles

- **Zero-Substitution Free:** Handles sparse data by maintaining geometric integrity without relying on arbitrary pseudo-counts.
- **External Anchoring:** References physical sampling depth and temporal sequences as external constraints to solve the unit-sum problem.
- **Subcompositional Invariance:** Mathematically ensures that the presence or absence of specific components does not distort the interpretation of the entire system.

---

### 3. Academic Citations

This system is developed based on the methodologies defined in the following works:

- **Aitchison, J. (2002).** DOI: [10.1111/1467-9876.00275](https://doi.org)
- **Ohta, T. (2011).** DOI: [10.1007/s11004-011-9332-y](https://doi.org)
- **Itagaki, T. (2024).** DOI: [10.3390/microorganisms12071484](https://doi.org)
- **Itagaki, T. (2025).** DOI: [10.3390/nu17233681](https://doi.org)
- **Itagaki, T. (2026).** DOI: 10.13140/RG.2.2.21953.93284
- **Itagaki, T. (2026).** DOI: 10.13140/RG.2.2.35015.25762

---

### 4. License
Copyright (c) 2026 Tatsuki Itagaki.
Licensed under the [MIT License](https://opensource.org).
