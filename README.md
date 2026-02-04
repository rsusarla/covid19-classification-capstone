
# COVID-19 Classification Capstone Project

## Project Overview
This project presents an end-to-end machine learning classification pipeline built on a COVID-19 patient dataset.  The goal is to predict COVID-19 infection status using patient demographic and clinical features, while emphasizing interpretability, evaluation rigor, and real-world limitations, rather than optimizing for accuracy alone.

The project was completed as a capstone-level data science project and follows industry-style structure, documentation, and evaluation practices.
---
## Problem Statement
Accurate and timely identification of COVID-19 cases is critical for clinical decision-making and public health response.  
Using structured patient data, this project investigates:

- Whether available features can reliably predict COVID-19 infection
- Which features contribute most to predictions
- How different classification models compare in performance and robustness

This is framed as a binary classification problem.
---
## Dataset Description
The dataset contains patient-level records with a mix of:
- Demographic attributes  
- Clinical indicators and symptoms  
- Health-related features relevant to COVID-19 infection  

### Target Variable
- COVID-19 Status (Binary classification)

### Notes on Data Usage
- Data preprocessing and cleaning were performed as part of the project
- Missing values, categorical encoding, and scaling were handled systematically
- Due to size/licensing considerations, the full dataset may not be stored directly in this repository

Details on dataset access are provided in the `data/README.md` file.
---
## Methods and Workflow

### 1. Exploratory Data Analysis (EDA)
- Univariate analysis to understand feature distributions
- Bivariate analysis to explore relationships with the target
- Correlation analysis for numerical variables
- Identification of missing values and data quality issues

**Key EDA Findings**
- No single feature strongly determines COVID-19 status
- Relationships are generally weak-to-moderate
- Suggests the need for multivariate modeling
---
### 2. Data Preprocessing
- Missing values handled using appropriate statistical methods
- Categorical variables encoded for machine learning compatibility
- Feature scaling applied where required
- Dataset split into training and testing sets to avoid data leakage
---
### 3. Models Implemented
The following classification models were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier

These models were selected to balance:
- Interpretability
- Non-linear learning capacity
- Bias–variance tradeoffs
---
### 4. Evaluation Metrics
Models were evaluated using multiple metrics to ensure balanced assessment:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Confusion matrices and ROC curves were generated for deeper diagnostic insight.
---
## Results Summary
- No single model achieved near-perfect performance
- Ensemble methods (Random Forest) demonstrated improved stability
- Performance tradeoffs between recall and precision were observed
- Results highlight the complexity and uncertainty inherent in real-world clinical prediction tasks
---
## Feature Importance and Interpretation
- Feature importance analysis was conducted for tree-based models
- Certain clinical indicators contributed more consistently than demographic variables
- Importance values indicate relative contribution, not causality
---
## Key Limitations
- Dataset features may not capture all clinically relevant factors
- COVID-19 diagnosis is influenced by testing availability, policy, and timing
- Predictive models should support, not replace, clinical judgment
---
## Visual Analytics
Interactive dashboards were created in Tableau Public to complement the modeling results and provide intuitive exploration of:
- Feature distributions
- Segment-level behavior
- Model outcomes

Tableau Public link (if applicable):
> *Add your Tableau Public URL here*
---
## How to Run This Project
1. Clone the repository
2. Install required libraries:
3. Run notebooks in order:
- Part 1: EDA
- Part 2: Preprocessing and Modeling
---
## Key Takeaways
- Demonstrates a complete ML workflow from raw data to interpretation
- Emphasizes responsible modeling and evaluation practices
- Highlights the gap between academic metrics and real-world decision-making
- Serves as a strong foundation for healthcare analytics and applied ML projects
---
## Author
RAMESH SUSARLA - This project was developed as part of a data science capstone to demonstrate applied machine learning skills, analytical reasoning, and professional documentation practices.

