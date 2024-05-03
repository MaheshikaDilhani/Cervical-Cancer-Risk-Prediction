# Cervical-Cancer-Risk-Prediction

Introduction

Cervical cancer is a significant health concern, with thousands of women affected annually. In this project, I leverage machine learning techniques to build a classifier that predicts the risk of cervical cancer in individuals. The dataset used contains information on 858 patients, including factors such as number of pregnancies, smoking habits, STD history, demographics, and medical records.

Objective

The primary goal of this project is to utilize Python libraries and machine learning algorithms to develop a predictive model for cervical cancer risk assessment. Through exploratory data analysis and model training, aim to understand the underlying patterns in the data and build an effective classifier.


•	Apply Python libraries to import and visualize dataset

•	Perform exploratory data analysis to understand data distribution and relationships.

•	Split and standardize training and testing dataset.

•	Train the XGBoost model using Scikit-Learn.

•	Evaluate and analyze the performance of classifier models.


Methodology

Data Import and Visualization: Utilized Python libraries to import and visualize the dataset for initial exploration.

Exploratory Data Analysis (EDA): Explored the distribution and relationships within the dataset to gain insights.

Data Preprocessing: Split the data into training and testing sets, and standardized the features.

Model Training: Utilized the XGBoost algorithm from Scikit-Learn to train the classifier.

Model Evaluation: Analyzed the performance of the classifier using appropriate evaluation metrics.



Model Evaluation

After training the XGBoost classifier, its performance was evaluated on the test dataset using the following metrics:

•	Precision: For class 1 (indicating the presence of cervical cancer risk), the precision achieved was 0.80.

•	Recall: Recall, also known as sensitivity, measures the ability of the classifier to correctly identify positive instances. For class 1, the recall achieved was 0.67.

•	F1-score: The F1-score is the harmonic mean of precision and recall, providing a balance between the two metrics. For class 1, the F1-score obtained was 0.73.


Conclusion

In conclusion, this project demonstrates the efficacy of machine learning techniques, particularly XGBoost, in predicting cervical cancer risk. By understanding the key factors contributing to the risk, healthcare professionals can better assess and manage the health of individuals at risk of cervical cancer.




