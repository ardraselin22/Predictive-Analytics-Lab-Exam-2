# Predictive-Analytics-Lab-Exam-2
 Predictive Analytics Lab Exam-2
The objective of this lab exam is to perform a binary classification task using machine learning techniques. The goal is to analyze the dataset, build a classification model, visualize decision boundaries, and evaluate model performance.

The dataset consists of 1020 observations. The features include Feature1 and Feature2, both of which are continuous variables. The target variable is binary, with values Yes and No, which are encoded as 1 and 0 respectively.

The categorical target values Yes and No were converted into numerical format 1 and 0. Rows with missing target values (20 rows) were removed. Outliers in Feature1 were identified and removed. StandardScaler was applied to normalize the feature values.

There were no missing values in the features, while some missing values in the target were handled. The class distribution was slightly imbalanced. The scatter plot showed that class 1 points were concentrated in the center, while class 0 points were more spread out. The dataset was not linearly separable.

Logistic Regression was used as a baseline model. It assumes a linear decision boundary. Its performance was limited because the data is not linearly separable.

The Decision Tree Classifier was used as the final model. It is capable of capturing non-linear relationships. It provides flexible decision boundaries and is better suited for this dataset.

The decision boundary was plotted for both models. Logistic Regression produced a linear boundary. The Decision Tree produced a non-linear boundary, which better fits the data.

The model achieved an accuracy of 0.96. The confusion matrix values are 152, 6, 2, and 40. For Class 0, the precision is 0.99, recall is 0.96, and F1-score is 0.97. For Class 1, the precision is 0.87, recall is 0.95, and F1-score is 0.91.

The model performs very well with a high accuracy of 96 percent. Misclassifications are minimal, with 6 false positives and 2 false negatives. Most errors occur near overlapping regions of the feature space. The slight class imbalance affects the precision of Class 1.

Logistic Regression underperformed due to its linear assumptions. The Decision Tree handled non-linearity effectively. Feature scaling improved model stability. Outlier removal improved both visualization and model performance.

The Decision Tree model outperformed Logistic Regression. It achieved high accuracy with minimal errors. It is suitable for datasets with non-linear patterns. This demonstrates the importance of selecting the right model based on data characteristics.

Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn were used for implementation.

Open the notebook in Google Colab. Upload the dataset named Lab_Exam_binary_classification_dataset.csv. Run all the cells sequentially. View the outputs, including EDA plots, decision boundaries, and model evaluation.

Ensemble methods such as Random Forest and Gradient Boosting can be used. Hyperparameter tuning can improve model performance. Class imbalance can be handled using resampling techniques. Advanced models like SVM with RBF kernel can also be explored.

Author
Ardra Selin A G
