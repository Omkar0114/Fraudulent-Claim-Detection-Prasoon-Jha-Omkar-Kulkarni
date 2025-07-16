# Fraudulent Claim Detection - Machine Learning Case Study

## Project Overview

This project implements a machine learning solution for detecting fraudulent insurance claims. The case study was developed for **Global Insure**, a leading insurance company that processes thousands of claims annually and faces significant financial losses due to fraudulent claims.

## Business Problem

Global Insure's current fraud detection process relies on manual inspections, which is:
- Time-consuming and inefficient
- Often detects fraud too late in the process
- Results in considerable financial losses after payouts

The company needed a data-driven solution to classify claims as fraudulent or legitimate early in the approval process to minimize financial losses and optimize the overall claims handling process.

## Project Objectives

1. **Build a predictive model** to classify insurance claims as fraudulent or legitimate based on historical claim details and customer profiles
2. **Analyze historical claim data** to detect patterns that indicate fraudulent claims
3. **Predict fraud likelihood** for incoming claims based on past data
4. **Provide actionable insights** to improve the fraud detection process

## Dataset

The project uses an insurance claims dataset with:
- **1,000 records** and **40 features**
- Features include claim amounts, customer profiles, incident details, vehicle information, and more
- Target variable: `fraud_reported` (binary classification)

### Key Features
- **Claim Information**: total_claim_amount, injury_claim, property_claim, vehicle_claim
- **Customer Profile**: age, gender, marital_status, education_level
- **Incident Details**: incident_type, collision_type, incident_severity
- **Vehicle Information**: auto_make, auto_model, auto_year
- **Geographic Data**: policy_state, insured_zip

## Methodology

### 1. Data Exploration and Analysis
- Comprehensive exploratory data analysis (EDA)
- Statistical analysis of feature distributions
- Correlation analysis between variables
- Data quality assessment and missing value analysis

### 2. Data Preprocessing
- Feature engineering and selection
- Handling categorical variables through encoding
- Feature scaling and normalization
- Addressing class imbalance using SMOTE

### 3. Model Development
Two machine learning models were implemented:

#### Logistic Regression Model
- Multicollinearity assessment using VIF analysis
- Recursive Feature Elimination with Cross-Validation (RFECV)
- Model training and evaluation
- Threshold optimization for better performance

#### Random Forest Model
- Feature importance analysis
- Cross-validation to prevent overfitting
- Hyperparameter tuning using Grid Search
- Final model optimization

### 4. Model Evaluation
- Performance metrics: Accuracy, Precision, Recall, F1-Score
- Confusion matrix analysis
- ROC-AUC curve evaluation
- Model comparison and selection

## Project Deliverables

1. **Jupyter Notebook**: Complete analysis and model implementation
   - `Fraudulent_Claim_Detection_Case study_Note book_Omkar-Kulkarni_Prasoon_Jha.ipynb`

2. **Project Report**: Detailed analysis and findings
   - `Fraudulent_Claim_Detection_Report_Prasoon_Kumar_Jha-Omkar_Kulkarni.pdf`

3. **Presentation**: Executive summary and key insights
   - `Fraudulent_Claim_Detection_PPT_Prasoon_Jha-Omkar_Kulkarni.pdf`

## Technologies Used

- **Python** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Scikit-learn** - Machine learning algorithms
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## Key Insights

The project provides valuable insights into:
- Patterns and characteristics of fraudulent claims
- Most important features for fraud detection
- Model performance comparison
- Recommendations for improving fraud detection processes

## Authors

- **Omkar Kulkarni**
- **Prasoon Jha**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Getting Started

1. Clone this repository
2. Extract the Jupyter notebook file
3. Install required Python packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```
4. Open the notebook in Jupyter Lab or Jupyter Notebook
5. Run the cells sequentially to reproduce the analysis

## Project Structure

```
├── README.md
├── LICENSE
├── Fraudulent_Claim_Detection_Case study_Note book_Omkar-Kulkarni_Prasoon_Jha.ipynb
├── Fraudulent_Claim_Detection_Report_Prasoon_Kumar_Jha-Omkar_Kulkarni.pdf
├── Fraudulent_Claim_Detection_PPT_Prasoon_Jha-Omkar_Kulkarni.pdf
└── Fraudulent_Claim_Detection_Case study_Note book_Omkar-Kulkarni_Prasoon_Jha.zip
```

---

*This project demonstrates the application of machine learning techniques to solve real-world business problems in the insurance industry.*
