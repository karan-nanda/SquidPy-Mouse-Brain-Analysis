# SquidPy
# Mouse Brain Spatial Analysis

Welcome to the GitHub repository for Mouse Brain Spatial Analysis! This project utilizes Python and various libraries such as Scanpy and Squidpy to perform comprehensive spatial analysis on a coronal section of a mouse brain. This README provides a brief overview of the code and its functionalities.

## Introduction

This code is designed to analyze the spatial organization of a mouse brain coronal section using single-cell RNA sequencing data. The primary goal is to uncover patterns, relationships, and interactions among different cell types within the brain tissue.

## Getting Started

To get started with this project, you'll need to have Python and the required libraries installed. You can install the necessary packages using the following:

```bash
pip install scanpy squidpy numpy pandas matplotlib seaborn
```

## Usage

The provided code includes a series of analysis steps, each contributing to the overall spatial analysis of the mouse brain data. Here's an overview of the main sections:

1. **Loading Data**: The code starts by loading the spatial transcriptomics data of the mouse brain section using Scanpy and Squidpy. The data includes information about cells, genes, counts, and various attributes.

10x Genomics. (2020, June 23). Mouse Brain Section (Coronal) – Spatial Gene Expression dataset (Space Ranger 1.1.0) [Data set]. 10x Genomics. https://www.10xgenomics.com/datasets/mouse-brain-section-coronal-1-standard-1-1-0

The above dataset is also available readily in squidpy dataset so you do not have to download the visium data yourself!

3. **Data Exploration**: This section explores the loaded data, displaying the dimensions and basic statistics of the AnnData object.

4. **Visualizing Data**: Different plots are generated to visualize the distribution of cell counts, gene counts, and other attributes across the tissue.

5. **Spatial Analysis**: The code then delves into spatial analysis. It uses Squidpy to compute spatial neighbors, neighborhood enrichment, co-occurrence, and ligand-receptor interactions. The results are visualized using heatmaps and plots to help identify patterns and relationships.

6. **Ripley's L Function**: The Ripley's L function is used to analyze spatial patterns and distributions of clusters within the tissue.

7. **Moran's I Score**: Moran's I score is calculated to assess the spatial autocorrelation of genes, indicating whether certain genes show clustering, dispersion, or randomness.

8. **SEPAL Score**: The SEPAL score (Spatial Exploratory Analysis of Ligands and Proteins) is computed to analyze cell-cell interactions based on gene expression profiles.

## Contributing

If you're interested in contributing to this project, feel free to fork the repository, make your changes, and submit a pull request. You can also report any issues or suggestions using the GitHub issue tracker.

## Credits

This project is made possible by the contributions of various open-source libraries, including Scanpy and Squidpy, as well as the Python programming community.


---

I hope you find this project insightful and valuable for your research on the spatial organization of the mouse brain. If you have any questions or need further assistance, don't hesitate to reach out via GitHub issues or other contact methods provided in the repository. Happy analyzing!
