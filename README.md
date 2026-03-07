## (WEKA Implementation)Data Mining

This project explores various **Data Mining techniques** and **Machine Learning models** using the **WEKA** platform. The primary objective was to evaluate model performance across different domains including classification, regression, clustering, and association rule mining.

### Key Datasets & Objectives

* **Iris Dataset**: Evaluated probabilistic, rule-based, and instance-based classifiers.


* **CPU Dataset**: Applied linear regression models to predict performance based on hardware specifications.


* **Breast Cancer Dataset**: Performed binary classification to predict recurrence events.


* **Supermarket Dataset**: Utilized association rule mining to find consumer purchasing patterns.


* **Weather Dataset**: Compared Decision Trees (ID3) against rule-based models (PRISM).



---

### Summary of Findings

#### 1. Classification (Iris & Breast Cancer)

* **Naïve Bayes & IB1** proved highly effective for the Iris dataset, achieving approximately **96% accuracy**.


* **Logistic Regression** (68.88% accuracy) outperformed the **Winnow** model on the Breast Cancer dataset, providing more reliable classification.



#### 2. Regression (CPU Performance)

* **Multiple Linear Regression** significantly improved accuracy over simple regression, achieving a strong **0.90 correlation coefficient**.


* Key performance influencers identified included cache memory (**CACH**) and maximum channels (**CHMAX**).



#### 3. Clustering & Association

* **Clustering**: Models like **K-Means**, **Cobweb**, and **Hierarchical Clusterer** successfully grouped species, confirming the natural structure of the Iris data.


* **Apriori**: Discovered a strong association between **Biscuits** and **Bread & Cake** with **92% confidence** and a **Lift of 1.27**.



---

### Tools Used

* **WEKA Explorer**: For preprocessing, classification, clustering, and visualization.


* **ARFF Files**: Standard attribute-relation file format for data input.



---

### Conclusion

The project demonstrates that model selection is highly dependent on the dataset's characteristics. While probabilistic models excelled at clear class separation (Iris), multiple regression was necessary to capture the complexity of hardware performance (CPU).
