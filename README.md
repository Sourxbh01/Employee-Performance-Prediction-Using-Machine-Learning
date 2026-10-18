# Employee Performance Prediction Using Machine Learning

## Project Overview
This project uses machine learning classification algorithms to predict employee performance categories based on employee-related data. The target categories are High Performer, Average Performer, and Low Performer.

## Objectives
- Analyze employee data using Exploratory Data Analysis (EDA).
- Clean and preprocess data for machine learning.
- Train and compare multiple classification models.
- Optimize model performance using hyperparameter tuning.
- Generate predictions for unseen employee records.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- CatBoost
- Google Colab

## Project Workflow
1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Missing-value imputation and categorical encoding
4. Train-validation split using stratified sampling
5. Model training and comparison
6. Random Forest hyperparameter tuning using GridSearchCV
7. Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix
8. Prediction generation and CSV export

## Models Implemented
- Decision Tree
- Random Forest
- Extra Trees
- CatBoost
- Tuned Random Forest

## Model Performance

| Model | Validation Accuracy |
|---|---:|
| Decision Tree | 86.50% |
| Random Forest | 88.00% |
| Extra Trees | 82.25% |
| CatBoost | 88.50% |
| Tuned Random Forest | **88.75%** |

The tuned Random Forest achieved the highest recorded validation accuracy among the tested models.

## Output
The selected model generates predictions for the test dataset and exports them to `employee_performance_submission.csv`.

## Key Learnings
- Data preprocessing and feature encoding
- Exploratory data analysis
- Supervised machine learning
- Model comparison and hyperparameter tuning
- Classification evaluation and prediction generation

## Future Improvements
- Perform additional cross-validation.
- Analyze feature importance.
- Evaluate fairness and potential bias.
- Test generalization on independent datasets.

## Conclusion
This project demonstrates an end-to-end machine learning workflow, from data exploration and preprocessing to model evaluation and prediction generation.

**Note:** Validation accuracy is an estimate of model performance and does not guarantee accuracy on unseen data.
