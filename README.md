# AI_FRAUD_DETECTION

This project implements an advanced AI-driven fraud detection framework for financial transactions, with a focus on companies in the Visegrad Group (Czech Republic, Hungary, Poland, Slovakia). The model integrates metaheuristic optimization (PSO + GA) with traditional machine learning and deep learning methods, aiming for >90% classification accuracy while ensuring transparency through explainable AI (LIME & SHAP).

# 📌 Overview

Fraudulent activities pose a significant risk to financial institutions. Traditional methods often fail to keep pace with sophisticated fraud tactics. This project introduces a hybrid probabilistic model that combines:

- **Particle Swarm Optimization (PSO)**

- **Genetic Algorithms (GA)**

- **Ensemble Learning**

- **Deep Learning (CNN, LSTM, Dense models)**

The model is tested on financial datasets of Visegrad companies, addressing challenges of imbalanced data and enhancing interpretability.

# 🚀 Features

## Data Preprocessing

- Missing value handling, categorical encoding, feature scaling.

- Class balancing using SMOTE/ADASYN.

## Exploratory Data Analysis (EDA)

- Univariate, bivariate, and multivariate analysis.

- Correlation heatmaps and feature engineering.

## Model Development

- Baseline models: Logistic Regression, Random Forest, XGBoost, Gradient Boosting.

- Advanced models: CNN, LSTM, Dense Neural Nets.

- Optimization with PSO & GA for ensemble classifiers.

## Model Interpretability

- LIME: Local instance-level explanations.

- SHAP: Feature contribution analysis.

## Performance

- Achieved validation accuracies up to 98.6% (PSO+Ensemble).

- Consistently outperformed traditional methods (Random Forest, XGBoost, etc.


# 📊 Results

- **GA + Ensemble: 97.8% accuracy**

- **PSO + Ensemble: 98.6% accuracy**

- **Interpolation Dense: 94.7% accuracy**

- **LIME & SHAP: 0.99–1.00 interpretability score**

These results significantly outperform traditional algorithms like Random Forest (54.4%) and XGBoost (55.5%).

# 🛠️ Tech Stack

- Languages: Python
- Libraries: Pandas, NumPy, Scikit-learn, TensorFlow/Keras, XGBoost, Imbalanced-learn, Matplotlib, Seaborn, LIME, SHAP
- Optimization: Genetic Algorithms, Particle Swarm Optimization

# 📂 Project Structure

- AI_FRAUD_DETECTION.ipynb    # Main notebook with implementation
- AI_FRAUD_DETECTION.pdf      # Project report
- AI_FRAUD_DETECTION.pptx     # Presentation
- requirements.txt            # modules needed to install
- README.md                   # Documentation (this file)

# 📹 Demo

### YouTube presentation: Watch here (https://www.youtube.com/watch?v=MrVW2XWWpcI)

# 🔮 Future Scope

- Validate models on real-world datasets beyond Visegrad companies.

- Extend fraud detection to blockchain, IoT, and healthcare domains.

- Develop adaptive models for evolving fraud patterns.

- Collaborate with financial institutions for deployment.
