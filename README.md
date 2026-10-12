# Data Mining with WEKA: Classification, Regression, Clustering and Association Rules

Five datasets, four kinds of data mining task, all run in WEKA Explorer. The goal was to see how the choice of algorithm depends on the data.

## Datasets and tasks

| Dataset | Task | Algorithms |
|---|---|---|
| Iris | Classification, clustering | Naive Bayes, IB1, rule learners; K-Means, Cobweb, Hierarchical |
| Breast Cancer | Binary classification (recurrence) | Logistic Regression, Winnow |
| CPU | Regression (performance) | Simple and multiple linear regression |
| Supermarket | Association rules | Apriori |
| Weather | Classification | ID3 decision tree, PRISM |

## Results

- **Iris:** Naive Bayes and IB1 both reached about 96% accuracy. The clusterers recovered the three species groups.
- **Breast Cancer:** Logistic Regression (68.88%) beat Winnow.
- **CPU:** multiple linear regression reached a 0.90 correlation coefficient, well above any single-variable model. Cache memory (CACH) and maximum channels (CHMAX) mattered most.
- **Supermarket:** Apriori found that customers who buy biscuits also buy bread and cake, with 92% confidence and lift 1.27.

Simple, well-separated data (Iris) suits probabilistic and instance-based classifiers, while hardware performance needed several predictors together.

## Files

| File | Contents |
|---|---|
| `Data_Mining_Project__Presentation.pptx` | Results with WEKA output screenshots |

Author: Muhammad Ehtesham · [LinkedIn](https://www.linkedin.com/in/muhammad-ehtesham-dsa)
