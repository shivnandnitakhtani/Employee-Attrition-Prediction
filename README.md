# Employee Attrition Prediction Model

A data-driven machine learning project designed to identify high-probability employee flight risks and provide strategic retention insights for corporate human resources.

## 📊 Model Performance Metrics
* *Algorithm Used:* Random Forest Classifier
* *Overall Accuracy:* 98.58%
* *Recall Rate:* 92.00% (High performance in capturing employees likely to leave)

## 💡 Key Business Insights
1. *Employee Satisfaction:* Low job satisfaction serves as the single strongest indicator of upcoming resignations.
2. *Workload Imbalances:* The number of projects heavily impacts turnover. Extreme distributions (too few or too many assignments) correlate with distinct flight-risk clusters.

## 🚀 Strategic HR Recommendations
* *Proactive Interventions:* Run the model's risk scoring system on a monthly basis to alert HR managers about high-probability flight risks before they formally resign.
* *Workload Optimization:* Actively monitor team members assigned to 6+ projects (burnout protection) or fewer than 3 projects (engagement protection) to balance workflows and maximize retention.

## 📁 Repository Structure
* project.ipynb - Core Jupyter Notebook containing data preprocessing, model training, and evaluations.
* random_forest_attrition_model.pkl - The final trained production-ready model saved via joblib.
* .gitignore - Python filter configuration keeping systemic junk files hidden.
* LICENSE - Open-source MIT license parameters.
