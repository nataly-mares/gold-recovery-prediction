# Gold Recovery Prediction

✅ Project Description
Zyfra, a company focused on efficiency solutions for the heavy industry, aims to optimize gold extraction processes.
This project consists of building a machine learning model to predict the amount of gold recovered from ore during the extraction and purification process.
The model is designed to support decision-making by improving production efficiency and identifying non-profitable parameters.
The evaluation metric used was sMAPE (Symmetric Mean Absolute Percentage Error), considering both rougher and final recovery stages.

✅ Objective
Build and evaluate regression models that can:
- Predict gold recovery at different stages of the process (rougher and final)
- Optimize production efficiency
- Identify key variables affecting extraction performance
- Minimize prediction error using sMAPE

✅ Methodology
- Data Preparation
- Load datasets (train, test, full)
- Validate data consistency
- Handle missing values and duplicates
- Align features between training and test sets
- Exploratory Data Analysis
- Analyze gold concentration across different stages
- Study distributions of key variables
- Detect anomalies and outliers
- Evaluate changes in metal concentration during purification
- Data Preprocessing
- Feature selection based on availability in test data
- Handling missing values
- Scaling (if required)

✅ Modeling

Multiple regression models were trained and evaluated:
- Linear Regression
- Tree-based models (e.g., Random Forest)
- Gradient Boosting models
- Key configurations:
- Separate prediction for:
- Rougher recovery
- Final recovery
- Custom evaluation metric: sMAPE
- Cross-validation for model selection

Additionally:
- Comparison of model performance
- Analysis of prediction errors
- Evaluation of generalization on test data

✅ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

✅ Results
The model successfully predicts gold recovery for both rougher and final stages.
sMAPE was effectively minimized, meeting the project requirements.
The analysis revealed that gold concentration increases through purification stages, confirming process consistency.
Feature selection and preprocessing played a key role in improving model performance.
