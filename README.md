# 🚀 Employee Attrition Predictive Pipeline: A Data-Driven Retention Strategy

## 📌 Executive Summary
Salifort Motors faced a significant challenge with employee turnover, impacting operational stability and recruitment costs. This project delivers a production-grade predictive pipeline designed to identify at-risk employees before they resign.

By transitioning from a baseline Logistic Regression to an optimized Random Forest Classifier, the model achieved a 92% Recall rate, successfully identifying the vast majority of attrition cases while providing actionable business insights.

## 🛠️ Tech Stack & Methodology

* **Language**: Python 3.x
* **Core Libraries**: Pandas (ETL), NumPy, Scikit-Learn (Modeling), Seaborn/Matplotlib (Visualization).
* **Architecture**: Modular functional programming focused on reproducibility and data integrity.

## Key Engineering Highlights:

* **Structural Data Audit**: Identified and neutralized a 20% redundancy bias (3,008 duplicate records) during the ingestion phase.
* **Feature Engineering**: Implemented Ordinal and One-Hot encoding to handle complex departmental and compensation variables.
* **Stratified Modeling**: Used stratified sampling to maintain class proportions, ensuring model robustness against imbalanced datasets.

## 📊 Strategic Business Insights

The analysis uncovered the "Breaking Point" for Salifort Motors' workforce:

1. **Burnout Threshold**: Attrition risk peaks when employees exceed 250 monthly hours or manage more than 5 simultaneous projects.
2. **Satisfaction Anchor**: Employee satisfaction is the strongest quantitative predictor; a drop below 40% signals imminent departure.
3. **The Retention Gap**: High-performing employees often leave due to workload-reward misalignment rather than lack of competence.

## 🏆 Model Performance


| Metric                             | Baseline (Logistic Regression) | Optimized Solution (Random Forest) |
|------------------------------------|--------------------------------|------------------------------------|
| Recall (Attrition Detection)       | 14%                            | 92%                                |
| Precision                          | 46%                            | 99%                                |
| Accuracy                           | 83%                            | 99%                                |


**Conclusion**: The Random Forest model provides a high-reliability early warning system, allowing HR to intervene proactively.

## 📂 Project Structure

├── data/  
│   └── HR_capstone_data.csv    # Raw dataset  
├── notebooks/  
│   └── attrition_pipeline.ipynb # Core ML Pipeline (Modular Code)  
├── outputs/  
│   └── confusion_matrix.png    # Visual evidence  
│   └── feature_importance.png  # Business drivers  
└── README.md   

## 🚀 How to Run

1. Clone the repository:

   ```Bash
   git clone https://github.com/your-username/hr-analytics-predictive-pipeline.git
   ```
   
2. Install dependencies:

    ```Bash
   pip install pandas numpy scikit-learn seaborn matplotlib
   ```

## 👤 Author
Anabelle Rodríguez
Senior Data Engineer | Analytics Specialist
[LinkedIn Profile](https://www.linkedin.com/in/anabelle-rodriguez-rivero-datdev/)
[Upwork Profile](https://www.upwork.com/freelancers/~01417cd8167d75f456?mp_source=share)
