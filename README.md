# # TitanicDataset Classification Project


This project applies exploratory data analysis and hyperparameter tuning in machine learning to predict passenger survival outcomes from the Titanic incident. Built and executed entirely within Google Colab, the workflow includes handling missing Values, feature engineering, and optimizing classification algorithms to achieve high prediction accuracy.



## Project Overview
* **Dataset:** Titanic Dataset (features include: Survived, Pclass, Name, Sex, Age,	SibSp, Parch,	Ticket,	Fare,	Cabin, Embarked).
* **Goal:** Identify Who survived or Not and build a predictive model
* **Libraries Used:** Python, Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib.



## Workflow
1. **Data Loading & Cleaning:** Importing the Titanic data structure.
2. **Exploratory Analysis:** Using `lmplots` to reveal linear relationships and find data distributions.
3. **Preprocessing:** Removed weak related features and splitting data into train/test sets.
4. **Model Training:** Training regression or classification models to predict performance scores.
5. **Hyperparameter Tuning:** The Hyperparameter Tuning using GridSearchCV
6. **Evaluation:** Assessing performance using baseline accuracy or error metrics.



## How to Run the Project
1. Click the **Open in Colab** badge at the top of this file.
2. Once the notebook opens in Google Colab, click **Runtime** in the top menu.
3. Select **Run all** to execute all code cells sequentially.


## Key Findings
* **Model Performance:** [SupportVectorMachine => Accuracy score:  0.9880952380952381 | KNNclassifier => Accuracy score: 0.9761904761904762]



