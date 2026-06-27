# Wine Quality Prediction Using KNN

Predicts wine quality using K-Nearest Neighbors algorithm.
Compares two approaches — Multiclass and Binary classification.

## Dataset
- Source: UCI Machine Learning Repository
- Rows: 1359 (after removing duplicates)
- Features: 11 chemical properties
- Target: quality score 3 to 8

## Approaches Compared

| Approach | Best K | Accuracy | F1 Score |
|----------|--------|----------|----------|
| Multiclass (3-8) | 11 | 0.6029 | 0.5822 |
| Binary (Good/Bad) | 12 | 0.7382 | 0.7359 |

## Key Learnings
- KNN mandatory requires feature scaling
- Binary classification outperforms multiclass by 13.5%
- Cross validation used to find optimal K value
- Rare quality scores (3, 4, 8) are hardest to predict

## Tech Stack
Python | Scikit-learn | Pandas | Matplotlib | Seaborn

## How to Run
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook wine_quality_knn.ipynb
