# KNN Classification – Bias-Variance Tradeoff
Mini project analyzing training/test error and decision boundaries using R.

## Project Summary
- Implemented a KNN classifier in R to classify 2D synthetic data.
- Evaluated training and test error for K = 1, 6, 11, …, 196.
- Visualized **bias–variance tradeoff** using error curves.
- Identified optimal K (116) with ~11.6% test error.
- Plotted decision boundary to interpret model predictions.

## Tools
- **R**, `class` package, `ggplot2`
- **LaTeX** for report formatting

## Files
- `mini_project_1.Rmd` – full code and report
- `mini_project_1.pdf` – compiled writeup with results
- `1-training_data.csv`, `1-test_data.csv` – sample datasets
- `error_plot.jpeg`, `decision_boundary.jpeg` – key visualizations


## Results
- Optimal K found: **116**  
- Training error ≈ 0.1186, Test error ≈ 0.1160
