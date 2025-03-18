# Stockout Risk Prediction using Rossmann Data


**#Project OverView**
This project predicts stockout risks in inventory management using the Rossmann Store Sales dataset from Kaggle.
The dataset is repurposed by simulating inventory levels (as 120% of average sales per store) and flagging days
when sales exceed this simulated inventory as "stockout" events.

**Methodology**
> Data Preprocessing:
Loading the dataset, simulating inventory levels, and creating a binary "stockout" indicator.
> Feature Engineering:
Extracting date features and one-hot encoding categorical variables.
> Handling Class Imbalance:
Applying SMOTE to the training data.
> Modeling:
Building and evaluating Logistic Regression, Decision Trees, and LightGBM models using AUC as a performance metric.

**# Results**
Logistic Regression AUC: 0.92
Decision Tree AUC: 0.90
LightGBM AUC: 0.96

**Conclusion**
We successfully built a machine learning pipeline that repurposes the Rossmann dataset for predicting stockout risks.
The pipeline demonstrates that advanced techniques like SMOTE and LightGBM can yield competitive performance.

**Future Work**
Enhance feature engineering with time-series analysis.
Explore ensemble methods or deep learning models.
Develop a dashboard for real-time monitoring.

**Acknowledgements**
Kaggle for the Rossmann dataset.
Open source libraries: pandas, scikit-learn, LightGBM, etc.