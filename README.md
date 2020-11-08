# Customer churn Classification

* Kaggle-Dataset containing 3333 costumers who either left (churn = 1) or stayed (churn = 0) in the company
* Dataset also included 10 features of the costumers including contract details and consumer-behavior
* Exploratory Data Analysis of Dataset
* Main insight: Costumers with high monthly charge and low data usage cancelled their service
* Build Machine-Learning-Models (such as Random Forest, XG-Boost) for the classification of costumers in the two groups
* The classes where imbalanced so I tried Upsampling and Downsampling; Upsampling yielded the better results
* **Accuracy on Test-Data:** XG-Boost (Accuracy: 95,2 %, AUROC: 91,7 %), Random Forest (Accuracy: 91,1 %, AUROC: 93,4 %)

![alt_text](https://github.com/abdumaa/Customer-churn-Classification/blob/main/__results___31_1.png)
