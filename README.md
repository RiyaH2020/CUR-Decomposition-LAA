CUR Matrix Decomposition

This repo contains an implementation and analysis of CUR matrix decomposition, an interpretable alternative to SVD for dimensionality reduction. Unlike SVD, which produces latent factors, CUR uses actual rows (R) and columns (C) from the dataset, making results easier to explain.

1. Contents

CUR_Decomposition.ipynb – Python implementation with experiments

LAA_Project_Report.pdf – Full project report

LAA_Project_Presentation.pptx – Summary slides

2. Highlights

Implemented probabilistic row/column sampling using leverage scores

Compared CUR with SVD on approximation error

Applied to GIST gene expression dataset for interpretable insights

3. Run It
git clone <repo_link>
cd CUR-Decomposition
jupyter notebook CUR_Decomposition.ipynb

4. Key Takeaway

CUR decomposition offers interpretability + competitive accuracy, bridging abstract linear algebra with real-world data analysis.
