# Single-Cell RNA-Seq Data Analysis

In this project, we analyze a single-cell RNA-seq dataset, with the goal of unveiling hierarchical structure and discovering important genes. The datasets provided are all different subsets of a larger single-cell RNA-seq dataset, compiled by the Allen Institute. This data contains cells from the mouse neocortex, a region in the brain which governs higher-level functions such as perception and cognition.

The single-cell RNA-seq data comes in the form of a counts matrix, where

each row corresponds to a cell

each column corresponds to the normalized transcript compatibility count (TCC) of an equivalence class of short RNA sequences, rescaled to units of counts per million. You can think of the TCC entry at location *(i, j)* of the data matrix as the level of expression of the *j*-th gene in the *i*-th cell.

Link to [Anaysis Report](https://drive.google.com/file/d/1uLvZA9hG6DdTa_IhlmZs-BQ1QhO0iwxu/view?usp=sharing)

## Folders
supervised - explore a small subset of the single-cell RNA-seq data, using visualization and clustering methods to discover its structure. 

  Notebooks
  [supervised.ipynb](https://github.com/tkayalvizhi/Gene_Expression_Level/blob/7cafdae51b784c1738e3317fc1c44091e8408ba3/supervised/supervised.ipynb)

unsupervised & unsupervised_evaluation - explore a larger subset of the data. Using clustering combined with logistic regression, discover informative features which can be used to distinguish cells of different types.

  Notebooks
  [hierarchical_clustering.ipynb](https://github.com/tkayalvizhi/Gene_Expression_Level/blob/7cafdae51b784c1738e3317fc1c44091e8408ba3/unsupervised/hierarchical_clustering.ipynb)
  [TSNE-perplexity_vs_learning_rate.ipynb](https://github.com/tkayalvizhi/Gene_Expression_Level/blob/7cafdae51b784c1738e3317fc1c44091e8408ba3/unsupervised/TSNE-perplexity_vs_learning_rate.ipynb)
  [evaluation.ipynb](https://github.com/tkayalvizhi/Gene_Expression_Level/blob/7cafdae51b784c1738e3317fc1c44091e8408ba3/unsupervised_evaluation/evaluation.ipynb)
