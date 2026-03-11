**Overview:**
The AI Bias Auditor is a machine learning auditing tool designed to detect and evaluate bias in predictive models. It analyzes model predictions across different demographic groups and measures fairness using statistical metrics. The goal is to identify potential discrimination in AI systems and promote transparent, fair, and responsible machine learning practices.

**Problem Statement:**
Machine learning models trained on real-world data can unintentionally learn and amplify societal biases. This can lead to unfair outcomes for certain demographic groups. The AI Bias Auditor aims to detect such biases by analyzing how a trained model performs across sensitive attributes like race, gender, or age.

**Objectives:**
Detect bias in machine learning model predictions
Compare prediction outcomes across demographic groups
Quantify bias using fairness metrics
Provide visual insights to interpret fairness results
Encourage responsible and ethical AI development

**Dataset:**
This project uses the COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) dataset, which has been widely used in fairness and bias research.
The dataset contains criminal justice data used to predict the likelihood of a defendant reoffending. It includes demographic and legal attributes that allow bias analysis.

**Key features include:**
Age
Race
Gender
Prior offenses
Recidivism outcome
The COMPAS dataset is commonly used to study fairness in machine learning because it highlights potential biases in predictive risk assessment systems.

**Methodology:**
1. Data Preprocessing
Handle missing values
Encode categorical variables
Select relevant features for modeling

2. Model Training
A Random Forest Classifier is trained to predict recidivism risk based on the available features.

3. Bias Evaluation
The trained model’s predictions are evaluated across demographic groups to identify disparities.

4. Visualization
Graphs and charts are generated to compare prediction outcomes between groups.

**Why Random Forest?**
Random Forest was selected because it:
Handles complex and non-linear relationships
Works well with structured tabular datasets
Reduces overfitting through ensemble learning
Provides strong baseline performance for fairness evaluation
Fairness Metrics Used
The system evaluates bias using several fairness metrics, including:
Statistical Parity Difference
Disparate Impact
Equal Opportunity Difference
Group-wise Accuracy Comparison
These metrics help determine whether the model treats demographic groups fairly.

**Results:**
The AI Bias Auditor highlights potential disparities in predictions between demographic groups. The fairness metrics and visualizations help identify whether certain groups are disadvantaged by the model. The model provides 89% accuracy.

**Future Improvements:**
Implement bias mitigation techniques
Add interactive dashboards for bias analysis
Evaluate additional fairness metrics
Support multiple datasets and models
