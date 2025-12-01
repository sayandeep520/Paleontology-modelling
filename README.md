
# Mammoth Extinction Modeling Project

This project explores the factors contributing to mammoth extinction through a series of ecological population models. We investigate the roles of climate variability, human hunting pressure, inter-species competition, and taphonomic biases in the fossil record.

## Key Findings:

*   **Model Calibration**: Initial calibration identified best-fit parameters for intrinsic growth rate (`r`) and human impact sensitivity (`h`) that best explain the observed last fossil occurrence of mammoths.
*   **Monte Carlo Simulation**: Stochastic simulations were used to assess model robustness and sensitivity to parameter variations. The initial single-species model was robust, showing no extinction within the simulated period with the calibrated parameters.
*   **Multi-Species Dynamics**: A two-species model incorporating competition between mammoths and a second herbivore demonstrated the impact of inter-species dynamics on population trajectories.
*   **Spatial Dynamics**: A multi-regional model further explored how regional climate, human pressure, and migration influence population distributions and survival.
*   **Hypothesis Testing (Climate vs. Human)**: Comparative analysis of Climate-Only, Humans-Only, and Combined models, using AIC scores, revealed that all models could explain the observed extinction timing with similar accuracy, highlighting the complexity of disentangling these drivers.
*   **Climate-Driven Taphonomy & Signor-Lipps Effect**: Simulations with climate-driven taphonomy demonstrated the Signor-Lipps effect, where the last synthetic fossil dates consistently appeared more recent than the true extinction dates, underscoring the bias in the fossil record.
*   **Sensitivity Analysis (r & h)**: A global sensitivity analysis generated an error landscape, identifying a 'valley of best fit' for `r` and `h` values that best match the observed extinction timing.
*   **Human Pressure Scenarios**: Different human pressure patterns (Linear, Blitzkrieg, Logistic) were tested. Surprisingly, the model showed insensitivity to the shape of human pressure, predicting the same extinction timing across all scenarios once a critical impact threshold was reached.
*   **Arrival Time Sensitivity**: The model was also insensitive to the exact human arrival time (within 10-20 kya BP), consistently predicting mammoth extinction at 5.00 kya, suggesting a dominant role for peak human pressure rather than its onset.
*   **Cross-Species Validation**: The model, with current parameters, did not successfully reproduce the differential extinction timing between Woolly Mammoths and Woolly Rhinos, suggesting a need for more species-specific parameterization or additional factors.

## Figures Generated:

*   `figure1_sensitivity_heatmap.png`: Sensitivity Analysis Error Landscape.
*   `figure2_abc_posteriors.png`: Posterior Distributions of `r` and `h` from ABC.
*   `figure3_ghost_lineage_taphonomy.png`: Ghost Lineage and Signor-Lipps Interval Visualization.
*   `figure4_arrival_time_comparison_late_only.png`: Mammoth Population Trajectory under Late Human Arrival Time.

To download this README, locate `README.md` in the Colab Files section and right-click to download.
