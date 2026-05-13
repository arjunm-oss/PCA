# PCA on Gene Expression Data

This project explores Principal Component Analysis (PCA) on gene expression data for dimensionality reduction and visualization.

The aim was to understand how PCA can help identify patterns and separation in biological samples using high-dimensional transcriptomics data.

## Files Included

- `filtered.tsv.gz` → filtered gene expression matrix
- `class.tsv` → sample class labels
- `columns.tsv.gz` → metadata/column information
- `Figure_1.png` and `Figure_2.png` → PCA visualizations
- `my_command.txt` → commands/workflow used during analysis

## What I Did

- Loaded and processed gene expression datasets
- Applied PCA for dimensionality reduction
- Visualized clustering/separation between samples
- Interpreted variance captured by principal components

## Tools Used

- Python
- pandas
- scikit-learn
- matplotlib
- numpy

## Running the Project

Clone the repository:

```bash
git clone https://github.com/arjunm-oss/PCA.git
cd PCA
```

Run the analysis script:

```bash
python file1.py
```

## Notes

This was mainly done as a learning project to better understand PCA and handling biological datasets.
