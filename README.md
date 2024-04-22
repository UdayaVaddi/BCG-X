# BCG-X
Demonstrating practical competence in critical areas of data science that include exploratory data analysis, feature engineering, and modeling. Through this project I have engaged in intensive tasks that culminated in strategic findings and actionable recommendations, showcasing an ability to translate business issues into data-driven solutions.
# Project Title: Churn Prediction for PowerCo
# Overview
As a Junior Data Scientist at BCG GAMMA, I undertook a simulation project to develop predictive models aimed at identifying the risk factors for customer churn at PowerCo, a prominent utility company providing gas and electricity. The goal was to leverage detailed exploratory data analysis and predictive modeling to understand key factors influencing customer decisions to discontinue services and to propose data-driven strategies to enhance customer retention.
# Objective
To predict customer churn using machine learning techniques and provide actionable insights to reduce churn rates effectively.
# Tools and Technologies
Python: For all data handling, processing, analysis, and modeling tasks.
Pandas & NumPy: For data manipulation and numerical calculations.
Scikit-Learn: For implementing machine learning algorithms.
Matplotlib & Seaborn: For data visualization.
Jupyter Notebook: For documenting the research process and findings.
# Project Description
# 1. Business Understanding & Hypothesis Framing
Purpose: Define the business problem, identify the key performance indicators, and hypothesize potential reasons for customer churn.
# Key Activities:
Problem Definition: Established that the primary business challenge was to understand factors contributing to customer churn, especially the impact of price sensitivity.

Stakeholder Engagement: Collaborated with senior data scientists and business stakeholders to align the project's objectives with PowerCo's strategic goals.

Hypothesis Development: Formulated hypotheses around price sensitivity, service quality, and contract flexibility influencing customer retention rates.

# 2. Exploratory Data Analysis (EDA)
Purpose: Explore and clean the dataset to prepare it for further analysis and feature engineering.
# Data Handled:
Customer Demographics: Age, location, type of premises (residential vs. commercial).

Service Details: Type of services availed (electric, gas), contract details.

Usage Patterns: Historical consumption data over the last five years.

Billing Information: Detailed records of pricing data, payment histories.

# Key Activities:
Data Cleaning: Addressed missing values, removed duplicates, and corrected data entry errors.

Statistical Summary: Generated descriptive statistics to get an overview of data distributions, outliers, and typical values.

Visualization: Created a series of plots including histograms, box plots, and scatter plots to visualize data distributions and relationships.

# 3. Feature Engineering
Purpose: Enhance the dataset with new features that could potentially improve the model's predictive accuracy.

# Techniques Employed:
New Feature Creation: Developed features like changes in consumption patterns, differences in billing amounts year-over-year, and categorical transformations of contract types.

Dimensionality Reduction: Applied principal component analysis (PCA) to reduce the number of features in highly dimensional data while retaining the most significant information.

Data Transformation: Normalized data to bring all features to a comparable scale, which is crucial for many machine learning models.

# Key Activities:
Feature Selection: Used correlation matrices and feature importance scores from preliminary models to select the most impactful features.

Dataset Enrichment: Integrated external data sources such as economic indicators and competitor information to provide a more comprehensive view.

# 4. Modeling and Evaluation
Purpose: Construct and evaluate a machine learning model to predict customer churn.
# Models Evaluated:
Logistic Regression: As a baseline for performance comparison.

Random Forest Classifier: Selected for its effectiveness in classification tasks involving complex and non-linear relationships.

Gradient Boosting Machines (GBM): For improving prediction accuracy through ensemble learning.

# Key Activities:
Model Training: Split data into training and testing sets. Configured and trained the models using cross-validation to find optimal parameters.

Performance Metrics: Evaluated models based on accuracy, precision, recall, and the AUC-ROC curve to assess and compare their performances.

Model Tuning: Applied grid search and randomized search techniques to fine-tune the hyperparameters and enhance model accuracy.

# 5. Insights & Recommendations
Purpose: Translate analytical findings into actionable business strategies to reduce churn.

Objective: To translate model findings into actionable business strategies for reducing customer churn.

Specific customer segments identified as high risk for churn.
# Recommendations:
Implement targeted communication and pricing strategies to retain high-risk segments.

Revise contract terms to offer more flexibility and competitiveness relative to market conditions.
# Insights Gained:
Price Sensitivity: High sensitivity particularly among the most profitable customer segments, suggesting a need
# Impact and Business Benefits
Enhanced understanding of factors contributing to customer churn enables PowerCo to strategically address these issues.

Predictive modeling assists in proactive customer retention efforts, potentially saving significant revenue and improving customer satisfaction.
# Repository Contents
README.md - Project overview and instructions.

data_analysis.ipynb - Jupyter notebook containing the exploratory data analysis.

feature_engineering.ipynb - Notebook detailing the feature engineering process.

model_building.ipynb - Notebook with model training, tuning, and evaluation.

presentation.pdf - Final presentation of insights and recommendations to stakeholders.

# Conclusion
This simulation provided hands-on experience in tackling real-world business problems using data science methodologies from hypothesis framing to delivering actionable insights, preparing me well for future roles in data science and analytics.
