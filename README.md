2D PCA Scatterplots: PC1 vs PC2, PC2 vs PC3, PC1 vs PC3

Pareto Chart: showing variance contribution of each component

3D PCA Plot: interactive visualization of PC1–PC3

Biplot: combined view of observations and variable loadings

💻 Requirements

Language: R

Packages:
RCurl, plyr, ggbiplot, rCharts, qcc, threejs, rgl, pca3d, gridExtra

Optional Installations:

# devtools::install_github("vqv/ggbiplot")
# devtools::install_github("bwlewis/rthreejs")

▶️ How to Run

Clone this repository

git clone https://github.com/<your-username>/PCA-Breast-Cancer.git
cd PCA-Breast-Cancer


Open the R Markdown file PCA_Breast_Cancer.Rmd in RStudio.

Run all code chunks sequentially.

Outputs include:

PCA summary and eigenvalues

Explained variance plots

2D and 3D PCA visualizations

🧠 Results Summary

PCA effectively reduces dimensionality while retaining the majority of the variance.

Visualization clearly separates benign from malignant classes in the lower-dimensional space.

The project demonstrates PCA’s usefulness in early diagnostic data analysis and feature reduction.

📚 References

UCI Machine Learning Repository. Breast Cancer Wisconsin (Original) Dataset.

R Core Team (2024). R: A Language and Environment for Statistical Computing.

Wickham et al. (ggplot2, plyr), Lewis (rthreejs), Vu (ggbiplot), etc.
