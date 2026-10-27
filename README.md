# Machine Learning – Practical Session 2

Standardized PCA: from scratch (NumPy) vs Scikit-learn.

## Files

- `solution_tp2.ipynb`: the notebook (Parts A, B and C)

## Requirements

```bash
python -m pip install numpy pandas matplotlib scikit-learn ipykernel
```

## Content of the notebook

**Part A – PCA from scratch:** load data, descriptive statistics, standardization, correlation matrix, eigenvalues/eigenvectors, sorting, projection on 2 components, explained variance.

**Part B – PCA with Scikit-learn:** `PCA(n_components=2)`, coordinates, explained variance.

**Part C – Comparison:** coordinates, eigenvalues, ratios, 2D plots, sign explanation, variance retained.

## Results

- PC1: 93.49 % of the variance
- PC2: 6.01 % of the variance
- PC1 + PC2: **99.50 %**
- Both methods give the same results, except that PC1 has the opposite sign (an eigenvector is defined up to a sign, so `v` and `-v` are both valid).
