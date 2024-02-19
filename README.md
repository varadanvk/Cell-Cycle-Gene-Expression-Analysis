# Cell Cycle Gene Expression Analysis

This repository contains code and analysis for exploring the relationships between RNA and protein expression levels across different phases of the cell cycle. The analysis is based on a dataset containing gene expression measurements for both RNA and protein levels during the G1, S, and G2 phases of the cell cycle.

## Dataset

The dataset used in this analysis is `Cell-Cycle-Set.xlsx`, which contains the following columns:

- `Gene_Name`: The name of the gene
- `mean_RNA_G1`: Mean RNA expression level during the G1 phase
- `mean_RNA_S`: Mean RNA expression level during the S phase
- `mean_RNA_G2`: Mean RNA expression level during the G2 phase
- `mean_protein_G1`: Mean protein expression level during the G1 phase
- `mean_protein_S`: Mean protein expression level during the S phase
- `mean_protein_G2`: Mean protein expression level during the G2 phase
- `GOBP`: Gene Ontology Biological Process annotation
- `GOMF`: Gene Ontology Molecular Function annotation
- `GOCC`: Gene Ontology Cellular Component annotation

## Analysis

The analysis is performed in the `Tutorial 1 - Computational Biology.ipynb` Jupyter Notebook. The notebook covers the following tasks:

1. **Data Cleaning and Exploration**: Import the dataset, handle missing values, explore basic statistics, and visualize distributions.
2. **Correlation Analysis**: Calculate pairwise correlations between RNA and protein levels at different cell cycle stages.
3. **Linear Modeling**: Fit linear models to explore the relationship between RNA and protein levels.
4. **Gene Subset Analysis**: Investigate subsets of genes based on Gene Ontology annotations, such as "cell cycle" and "ribosome".
5. **Cell Cycle Dynamics**: Calculate changes in RNA and protein levels across cell cycle stages and explore clustering and correlations among gene subsets.

The notebook contains detailed explanations, code, and visualizations for each step of the analysis.

## Requirements

The analysis was performed using Python 3.7 and the following libraries:

- pandas
- numpy
- matplotlib
- scikit-learn

To run the notebook, you'll need to have these libraries installed. You can install them using pip:

```
pip install pandas numpy matplotlib scikit-learn
```

## Usage

1. Clone this repository to your local machine:

```
git clone https://github.com/your-username/cell-cycle-gene-expression-analysis.git
```

2. Navigate to the repository directory:

```
cd cell-cycle-gene-expression-analysis
```

3. Open the Jupyter Notebook:

```
jupyter notebook
```

4. In the Jupyter Notebook interface, open the `Tutorial 1 - Computational Biology.ipynb` notebook and follow along with the analysis.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
