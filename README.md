# STA4143-Project
Student Performance Analysis and Prediction
Project Goal
The goal of this project is to analyze the factors that influence student academic performance and to build a predictive model that estimates a student's Math Score. By identifying key predictors such as Reading and Writing scores, gender, and socio-economic factors (like lunch programs), this project aims to provide educators with a transparent tool for identifying students who may need additional academic support.

Dataset
The project utilizes a Student Performance Dataset (sourced from Kaggle). The data includes several categorical and numerical features:

Target Variable: math score

Predictors: reading score, writing score, gender, race/ethnicity, parental level of education, lunch (standard vs. reduced), and test preparation course.

During the data wrangling phase, categorical variables were encoded (e.g., mapping education levels and gender to numerical values) to prepare the data for machine learning algorithms.

Model and Methodology
The analysis follows a standard data science workflow:

Exploratory Data Analysis (EDA): Visualized score distributions and correlations using histograms and boxplots.

Data Splitting: The dataset was split into a training set (80%) and a test set (20%).

Modeling: A Decision Tree Regressor was selected for its interpretability. To prevent overfitting and ensure clarity, the tree depth was constrained for visualization.

Evaluation: The model's performance was evaluated using Mean Absolute Error (MAE).

Results
Baseline MAE: 11.12

Model MAE: 5.47

The model significantly outperformed the baseline, reducing the error by approximately 50%. The analysis revealed that Reading Score is the strongest primary predictor of Math performance, followed by Writing scores and Gender.

Repository Contents
Project.ipynb: The complete data analysis and modeling notebook.

README.md: Project overview and summary of findings.

student.csv: Dataset used.
