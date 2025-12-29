# Home Credit Indonesia - Default Risk Prediction Model

## 🎯 Project Overview
This project develops a machine learning model to predict loan default risk for Home Credit Indonesia, as part of Rakamin Academy's Data Science Virtual Internship.

**Key Objectives:**
- Identify high-risk loan applicants accurately
- Provide data-driven insights for credit decision-making
- Suggest actionable business recommendations

## 📊 Methodology
| Step | Description | Notebook |
|------|-------------|----------|
| 1. Data Loading & Exploration | Initial data inspection and understanding | `01_data_loading.ipynb` |
| 2. EDA & Preprocessing | Data cleaning, visualization, and feature engineering | `02_eda_preprocessing.ipynb` |
| 3. Model Training | Implementing Logistic Regression and Random Forest | `03_model_training.ipynb` |
| 4. Model Evaluation | Performance comparison and metric analysis | `04_model_evaluation.ipynb` |
| 5. Business Insights | Extracting actionable business recommendations | `05_business_insights.ipynb` |

## 🏆 Key Results
- **Best Model:** Random Forest Classifier
- **ROC-AUC Score:** 0.721
- **Key Predictors:** External credit scores, income level, applicant age
- **Business Impact:** Potential 18.5% improvement in risk assessment accuracy

## 💡 Key Insights
1. **External credit scores** (`EXT_SOURCE_2`, `EXT_SOURCE_3`) are the strongest default predictors
2. **Income-to-credit ratio** above 2.5 indicates 3× higher default risk
3. **Applicants aged 40-49** show the lowest default rates (6.8%)

## 🚀 How to Use
```bash
# Clone repository
git clone https://github.com/FaisalSM27/home-credit-risk-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
