**Project Overview**
Depression among students is a growing concern worldwide, often resulting from
academic stress, social pressure, financial difficulties, and personal challenges.
Early detection of depressive tendencies can play a vital role in providing timely
intervention and support. Traditional methods, such as counseling sessions and
surveys, are often limited by their subjective nature, time consumption, and lack of
scalability.To address these limitations, this project proposes the development of a Student
Depression Detection AI Model. The system leverages Artificial Intelligence and
Machine Learning techniques to analyze student-related data—such as responses to
questionnaires, academic performance, attendance, behavioral patterns, and even
textual or social media content—to identify indicators of depression. By detecting
risk levels early, the model aims to provide a reliable decision-support tool for
universities, counselors, and healthcare professionals to better monitor student
mental health and take preventive action.This model not only aids in identifying students at risk but also contributes toward
reducing stigma by providing an automated, confidential, and unbiased assessment
system. It is envisioned as part of a broader mental health support framework that
enhances student well-being and academic success.

**Dataset Description**
Dataset Source: https://www.kaggle.com/datasets/adilshamim8/student-
depression-dataset. Number of Rows: 140,699 (Balanced 41.7% - 58.3%split). Number of Features: 18. Purpose: Predict whether a student is depressed or not.

**Roles of the group members**
IT24102351- R.M.Islah - Feature Creation, Data Imputation & Estimation
IT24102326-Dadallage.S - Data Representation
IT24102380-Fernando K.S.N.A - Feature Scaling
IT24102325-Muditha Bimsara K.P - Feature Selection & Reduction
IT24102361- Sharanjan. S - Data Discretization
IT24102357- Jayasinghe J.A.K.N - Data Cleaning

**How to run code?**

To run the code for this project, we ensured that Python 3.x is installed along with the required libraries such as pandas, numpy, matplotlib, seaborn, scikit-learn, and imbalanced-learn. The dataset file, named Student Depression Dataset.csv, should be placed inside the data/raw/ folder, as this is the path specified in the code. The dataset can be read into the program using the pandas library with the command pd.read_csv("Student Depression Dataset.csv", sep=";"), where the separator is explicitly defined because the dataset uses a semicolon delimiter. Each group member has developed their own preprocessing notebook located in the notebooks/ directory, and these can be opened and executed step by step using Jupyter Notebook. After running the individual notebooks, the integrated pipeline notebook named final(AIML).ipynb should be executed to combine all preprocessing techniques, generate the exploratory data analysis visualizations, and produce the final cleaned dataset. The processed dataset will then be automatically saved in the results/outputs/ folder as student_depression_features (2).csv, which can be used for further model training or analysis.
