# Categorical-Naive-Bayes-Implementation
Implementation of Categorical Naive Bayes classification algorithm in Python using Pandas, NumPy and Scikit-Learn.

Classifier is being fit with "categ.csv" dataset. Then it's tested on both "categ.csv" and "categ2.csv" datasets.

Both datasets have information about clothing.

Datasets characteristics:
- Number of instances: 1000
- Number of attributes: 5 (including target attribute), all categorical
- Attribute information:
  - size (XS, S, M, L, XL, XXL, 3XL)
  - material (nylon, polyester, silk, cotton, linen)
  - color (white, cream, blue, black, orange, green, yellow, red, violet, navy)
  - sleeves (short, long)
  - demand (low, medium, high)

The goal of classification task - predicting clothing demand based on the rest of the attributes.
