# Online appendix for "Evaluating Interactive 2D Visualization as a Sample Selection Strategy for Biomedical Time‑Series Data Annotation" by Vaaras et al. (2026)

This repository contains an additional appendix for the following publication (**NOTE: arXiv pre-print only, publication venue not yet confirmed**):
[E. Vaaras, M. Airaksinen, and O. Räsänen, "Evaluating Interactive 2D Visualization as a Sample Selection Strategy for Biomedical Time‑Series Data Annotation", _(arXiv pre-print, publication venue will be updated here later)_](https://arxiv.org/abs/2603.26592). The appendix contains 2D visualizations of both annotator-level and annotator group-level label distributions.

If you use any of the appendix content or their derivatives, please cite the [aforementioned publication](https://arxiv.org/abs/2603.26592).

## Description
This repository contains two folders named `TASK_2D_visualizations`, where TASK is either IMA (= infant motility assessment) or SER (= speech emotion recognition). Both of these folders contain two folders:
- `distributions_by_annotator_group`: Contains 2D visualizations of label distributions, organized by annotator group ("expert annotators", "non-expert annotators", and "all annotators").
- `distributions_by_annotator_id`: Contains 2D visualizations of label distributions, organized by annotator group ("expert annotators", "non-expert annotators", and "all annotators") and annotator ID (either 1, 2, or 3).

These folders, on the other hand, contain folders `pca`, `tsne`, and `umap`, representing 2D visualizations for the PCA, t-SNE, and UMAP visualization algorithms, respectively. For further information, refer to the [aforementioned publication](https://arxiv.org/abs/2603.26592).
