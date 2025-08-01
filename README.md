# ECTO_system_walkthrough
Official codebase accompanying the preprint:  “Behavioral Traits as Dynamical Systems: Utilizing Entropy to Analyze Longitudinal Psychometric Data in Coupled Ordinary Differential Equations”  by Anderson M. Rodriguez (2025) https://doi.org/10.48550/arXiv.2506.20622

#NOTE: Begin with ECTO_walkthrough_suite Notebook which will replicate, in order, all the main findings and plottings of the ECTO introductory paper.

# Overview:
This repository provides a complete walkthrough of the ECTO modeling process (Entropy Coupled Trait ODEs) for analyzing behavioral trait dynamics from longitudinal psychometric data. The model integrates:

- Shannon entropy (from Likert-scale distributions)
- Recursive trait-environment feedback via ODEs
- Lyapunov-proxy divergence analysis for temporal stability

The system is designed to test whether traits such as neuroticism are emergent attractors under metabolic, pleiotropic, and environmental constraints.

---

#Repository Contents:

| File | Description |
|------|-------------|
| `01_entropy_from_likert_data.ipynb` | Converts raw Likert-scale trait distributions into normalized entropy trajectories over time |
| `02_ECTO_trait_analyzer.ipynb`     | Simulates trait behavior under ECTO's system of coupled ODEs |
| `03_lyapunov_proxy_analysis.ipynb` | Measures empirical trait divergence using a Lyapunov-like local divergence metric |


#Quick Start

To run locally:

```bash
git clone https://github.com/amr28693/ECTO_system_walkthrough.git
cd ECTO_system_walkthrough
jupyter notebook

If you use this repository in your work, please cite:
Rodriguez, A. M. (2025). Behavioral Traits as Dynamical Systems: Utilizing Entropy to Analyze Longitudinal Psychometric Data in Coupled Ordinary Differential Equations.
Preprint available at: https://doi.org/10.48550/arXiv.2506.20622
