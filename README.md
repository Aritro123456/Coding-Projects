# Coding Projects

A collection of machine-learning research notebooks focused on practical classification problems in healthcare and finance. These projects show my workflow for exploring datasets, preparing data, training multiple models, tuning parameters, and evaluating results with clear metrics and visualizations.

## Projects Included

### Fetal Health Classification

Notebook: `Fetal_health.ipynb`

This project studies fetal health prediction using cardiotocography-style data. The goal is to classify fetal health conditions from clinical measurements and compare model performance across different machine-learning approaches.

Key work:
- Data loading and exploratory data analysis
- Correlation analysis and heatmap visualization
- Class balancing and train-test splitting
- Model training with Random Forest, Decision Tree, KNN, SVM, Logistic Regression, XGBoost, LightGBM, Extra Trees, Voting, and Stacking classifiers
- Hyperparameter exploration using validation curves and grid/random search
- Evaluation using accuracy, confusion matrix, classification report, ROC curve, and AUC

Related notebook:
- `Previous_Fetal_Health .ipynb` contains an earlier experimental version of the fetal health analysis.

### Loan Approval Research

Notebook: `Loan_Research_Approval.ipynb`

This project explores loan approval prediction using applicant and financial data. The notebook focuses on preprocessing, feature analysis, outlier handling, and comparing classification models for approval prediction.

Key work:
- Exploratory data analysis with statistical summaries and visualizations
- Box plots, histograms, and distribution analysis
- Outlier detection and removal using statistical methods and z-scores
- Feature scaling and encoding
- Model training with Logistic Regression, Decision Tree, Random Forest, KNN, SVM, XGBoost, LightGBM, Gradient Boosting, Bagging, MLP, Voting, and Stacking classifiers
- Evaluation using accuracy, precision, recall, F1-score, ROC-AUC, confusion matrix, and classification reports

Related notebooks:
- `Loan_Research_Approval-Copy1.ipynb`
- `Loan_Research_Approval-Copy2.ipynb`

These copies preserve additional experiment versions and iterations.

## Skills Demonstrated

- Python for data science
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature scaling and encoding
- Outlier detection
- Supervised machine learning
- Ensemble learning
- Hyperparameter tuning
- Model evaluation and comparison
- Data visualization
- Research-style experimentation in Jupyter Notebook

## Tech Stack

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- XGBoost
- LightGBM
- imbalanced-learn
- SciPy

## Repository Structure

```text
Coding-Projects/
├── Fetal_health.ipynb
├── Previous_Fetal_Health .ipynb
├── Loan_Research_Approval.ipynb
├── Loan_Research_Approval-Copy1.ipynb
├── Loan_Research_Approval-Copy2.ipynb
└── README.md
```

## How To Run

1. Clone the repository:

```bash
git clone https://github.com/Aritro123456/Coding-Projects.git
```

2. Open the folder:

```bash
cd Coding-Projects
```

3. Install the main Python libraries:

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn xgboost lightgbm imbalanced-learn scipy tabulate wordcloud openpyxl
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open any `.ipynb` file and run the cells.

Note: Some notebooks reference local dataset files such as Excel files. If a dataset file is not included in the repository, add the dataset to the project folder and update the file path inside the notebook before running.

## Why This Repository Matters

This repository demonstrates my ability to take real-world datasets from raw analysis to model evaluation. The notebooks show not only model training, but also the steps that matter before training: understanding the data, handling imbalance and outliers, comparing algorithms, and interpreting results through metrics and visualizations.

## Author

**Aritro**  
GitHub: [Aritro123456](https://github.com/Aritro123456)
