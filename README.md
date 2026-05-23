# Drift-Aware Temperature Scaling for Model Calibration under Distribution Shift

> Research project focused on drift-aware temperature scaling and calibration techniques for improving predictive reliability under distribution shift in deep learning systems.

This repository contains research work investigating calibration reliability and predictive uncertainty under distribution shift conditions. The project introduces and evaluates drift-aware temperature scaling approaches designed to improve confidence estimation and calibration robustness in deep learning models operating under data drift scenarios.

## Overview

Modern deep learning systems frequently exhibit overconfident predictions, particularly when deployed in environments where the input distribution differs from training conditions. Standard calibration techniques such as temperature scaling often degrade under distribution shift, resulting in unreliable confidence estimates and reduced trustworthiness.

This project explores drift-aware calibration strategies that adapt predictive confidence behavior according to estimated distributional drift. The work investigates how drift-sensitive calibration mechanisms can improve uncertainty estimation and maintain more reliable predictive behavior under shifting data distributions.

## Objectives

- Investigate predictive calibration under distribution shift
- Analyze confidence behavior under drift conditions
- Evaluate drift-aware temperature scaling methodologies
- Measure calibration quality using statistical evaluation metrics
- Improve reliability and uncertainty estimation in deep learning systems

## Methods and Approaches

The project utilizes:
- Temperature scaling calibration
- Drift-aware confidence adjustment
- Mahalanobis drift estimation
- Statistical reliability analysis
- Calibration error evaluation
- Predictive uncertainty estimation

## Technologies Used

- Python
- PyTorch
- Scikit-learn
- SciPy
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Repository Structure

```text
drift-aware-temperature-scaling/
│
├── notebooks/
│   └── drift_aware_temperature_scaling.ipynb
│
├── figures/
│   ├── distribution_shift_drift_scores.png
│   ├── mahalanobis_drift_distribution.png
│   ├── drift_vs_confidence_distribution_shift.png
│   ├── reliability_diagram_in_domain.png
│   ├── alpha_sensitivity_analysis.png
│   └── alpha_sensitivity_brier_score.png
│
├── paper/
│   └── manuscript_under_review_sncs.pdf
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## Evaluation Metrics

The project evaluates calibration performance using:
- Expected Calibration Error (ECE)
- Brier Score
- Reliability Diagrams
- Confidence Distribution Analysis
- Drift Sensitivity Evaluation
- Distribution Shift Analysis

## Key Findings

- Distribution shift significantly impacts predictive confidence calibration and uncertainty estimation.
- Drift-aware temperature scaling improves calibration reliability under shifted distributions.
- Mahalanobis-based drift estimation provides meaningful signals for adaptive calibration adjustment.
- Calibration quality varies substantially with drift sensitivity strength parameters.
- Drift-aware calibration techniques improve robustness compared to standard static temperature scaling approaches.

## Figures and Visualizations

The repository includes:
- Drift score distribution analysis
- Mahalanobis drift visualization
- Reliability diagrams
- Drift versus confidence analysis
- Alpha sensitivity evaluation plots
- Calibration performance visualization

## Research Paper

The accompanying manuscript is currently under review at SN Computer Science (Springer).

The paper is included in the `paper/` directory for academic reference and reproducibility purposes.

## Reproducibility

### Installation

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/drift_aware_temperature_scaling.ipynb
```

## Future Work

- Adaptive online calibration under dynamic drift conditions
- Bayesian uncertainty estimation methods
- Multi-domain calibration benchmarking
- Real-time calibration monitoring systems
- Calibration-aware deployment strategies for foundation models

## License

This project is licensed under the MIT License.

## Author

Shivaansh Sharma
