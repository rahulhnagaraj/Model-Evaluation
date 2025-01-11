# Model-Evaluation
Documentation Summary (Detailed)
Project Title: **Analyzing Diabetes Prediction with Logistic Regression, SVM Models, and EDA**
Objective:
**The goal of this project was to predict diabetes readmission rates using machine learning models, explore relationships within the dataset, and evaluate model performance through statistical metrics.**
Steps Taken:
1.	**Data Import and Preprocessing:**
	-Loaded the dataset and performed exploratory data analysis (EDA).
	-Checked for missing values, inconsistencies, and duplicates in the data.
	-Encoded categorical variables and created a consolidated readmission column to classify outcomes as NO or >30.
2.	**Exploratory Data Analysis (EDA):**
	-Visualized trends and distributions of key features, including readmission rates and demographic details.
	-Assessed correlations between features and their potential impact on predictions.
	-Used plots like histograms, box plots, and bar charts for insights.
3.	**Feature Engineering:**
	-Encoded categorical variables using one-hot encoding.
	-Standardized numerical data for consistent scaling across features.
4.	**Model Training:**
	-Trained two machine learning models:
	-Logistic Regression (LR): A baseline model for binary classification.
	-Support Vector Machines (SVM): Evaluated using linear kernel and hyperparameter tuning.
5.	**Model Evaluation:**
	-Measured model performance using:
	-Confusion Matrix: Assessed precision, recall, and accuracy for both LR and SVM.
	-ROC Curves and AUC: Compared LR and SVM models on their ability to classify readmissions.
	-Visualized both models' ROC curves on a combined plot for direct comparison.
6.	**Findings:**
	-Logistic Regression provided reasonable performance and interpretability.
	-SVM showed better performance metrics after optimization.
	-Both models captured the trends in the dataset effectively, highlighting the potential of machine learning in healthcare prediction tasks.
Conclusion:
**The project successfully demonstrated the use of EDA and machine learning for healthcare analytics. Logistic Regression served as a simple yet effective baseline, while SVM improved prediction performance. This work highlights how data-driven solutions can address clinical challenges such as diabetes readmission rates.**

