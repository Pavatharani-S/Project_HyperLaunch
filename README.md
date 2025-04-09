# Project_HyperLaunch
Project Title:
Disease Prediction Using Random Forest Classifier
________________________________________
Objective:
To build a machine learning model using Random Forest that predicts the most likely disease based on multiple symptoms provided by the user.
________________________________________
Dataset Overview:
The dataset contains rows of patient data where each column represents a symptom (e.g., fever, nausea, headache), and the final column (prognosis) indicates the diagnosed disease.
 Key Columns:
Column Name	 Description
Influenza	Binary (0/1) - Presence of symptom
Common Cold	Binary (0/1) - Presence of symptom
Asthma	Binary (0/1) - Presence of symptom
...	More symptoms
prognosis	Categorical - Disease name (e.g., Dengue)
•	Total Symptoms: ~100
•	Total Diseases (Prognosis): ~40
________________________________________
Technologies & Libraries:
•	Python 3
•	pandas, numpy – Data preparation
•	scikit-learn – Machine Learning
•	matplotlib, seaborn – Visualization
________________________________________
Machine Learning Model:
•	Random Forest Classifier
o	Ensemble method with multiple decision trees.
o	High accuracy and resistant to overfitting.
o	Works well with large feature spaces (many symptoms).
________________________________________
Workflow:
1.	Load the dataset
2.	Convert symptoms and target labels into numerical format
3.	Split the data into training and test sets
4.	Train the Random Forest Classifier
5.	Evaluate the model using:
     o	Accuracy
     o	Confusion Matrix
     o	Classification Report
6.	Predict disease for new input symptoms
________________________________________
Example Use Case:
A user enters symptoms like:
•	fever: Yes
•	cough: Yes
•	Blood Pressure: Yes
•	Cholesterol: Yes
The model predicts: Influenza
________________________________________
Conclusion:
•	The Random Forest model can accurately classify multiple diseases based on symptoms.
•	Can be extended into a web app for healthcare support.

