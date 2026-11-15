# Groundwater Level Prediction and Risk Classification

This project uses open government data to study groundwater in Haryana,
Gujarat and Maharashtra. It predicts the 2022 water depth of 1,848
monitoring wells from their 2015–2021 history, classifies each well into
one of four risk classes (Safe, Watch, Critical, Severe), and groups 33
districts by groundwater stress.

**Data:** Atal Bhujal Yojana disclosed groundwater level data, 2015–2022,
from data.gov.in (Ministry of Jal Shakti).

**Main finding:** groundwater depth changes slowly, so the simple rule
"next year equals last year" is very hard to beat. The best models only
match it. The most useful results are the district clusters and the
ranking of the districts that need attention first.

## Notebooks (run in order)
1. Exploring data
2. Preprocessing
3. Regression
4. KNN and Naive Bayes
5. Decision Tree and SVM
6. Clustering
7. PCA, neural network, ensembles and final comparison

Also included: an interactive dashboard (groundwater_dashboard.html)
and the project report.
